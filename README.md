#include <stdio.h>
int main()
{
int
days,hours,minutes,seconds,total_days_seconds,total_min_hours,total_minutes_
seconds,total;
scanf("%d",&days);
scanf("%d",&hours);
scanf("%d",&minutes);
scanf("%d",&seconds);
total_days_seconds=days*86400;
total_min_hours=hours*60;
total_minutes_seconds=(total_min_hours+minutes)*60;
total=total_days_seconds+total_minutes_seconds+seconds;
printf("%d seconds",total);
return 0;
}

