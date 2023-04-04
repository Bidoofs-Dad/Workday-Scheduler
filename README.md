# Workday-Scheduler

## About The Application

This is a handy scheduling calendar, that will help you keep track of your tasks for the day (in a 9 to 5 sense)! Upon pressing the 'save' button next to each time of day (after adding a task) it will then be saved to the local storage, and in return display it in the same location, even after refreshing! The scheduler is also color coordinated, the scheduler will look at your current time's hour, if the task is before your current hour, it will have a grayish background, if the task is in your current hour, then the background will be red and if the task is yet to come, the background will be green!

On top of that, the page displays the current time above the scheduler in the format of "Weekday, Month Name and Day  of the Month"!

## Issues

There was a few of us that worked together in a study group to knock this challenge out! We definitely ran into some issues here and there with the code, but in the end were able to get it all solved and turned into a perfectly working application! I will list a few of the challenges we encountered below though;

* The first challenge was navigating how to properly set values inside of local storage (values that the user sets, not pre-determined values, I should say).

* The second biggest issue after that, was calling the information out of local storage again, but we found the solution to that too! We wound up using some commands that were brand new to us, but were able to pick them apart and learn how they worked!

* The final main obstacle was how to turn the 'hour-x' ids into some form of integer,, so we could reference them together with dayjs. In the end we were able to do just that, again by using another couple commands that we had found ourselves!

## Screenshots

I will list some screenshots of the scheduler in working order below!

![Workday-Scheduler](/assets/images/01.png)
![Workday-Scheduler](/assets/images/02.png)
![Workday-Scheduler](/assets/images/03%20stored%20in%20local%20storage.png)
![Workday-Scheduler](/assets/images/04%20after%20refreshing%20the%20page.png)
![Workday-Scheduler](/assets/images/05%20show%20color%20change%20after%20new%20hour.png)

## Conclusion

In conclusion, this was a fun yet difficult challenge. Working together with some classmates was incredibly helpful, as we all seemed to come up with ways to solve different issues that we were all having, all in all, I was surprised with how quick we were able to get through this project, but that may just be the power of teamwork!

## The Link

Below is the link that will take you to the live website, hosted by GitHub Pages!

https://bidoofs-dad.github.io/Workday-Scheduler/