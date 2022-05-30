# bikesharing

[link to dashboard](https://public.tableau.com/app/profile/tom.snarsky/viz/CitiBikeChallengeBook/ChallengeStory?publish=yes)

## Overview of the statistical analysis

In this analysis we will be examining data from Citi Bike in New York City in order to evaluate the feasibility of launching a new Citi Bike program in Des Moines, Iowa. In order to narrow our focus we will be looking at one month's worth of data, pulled from the Citi Bike System Data archives. We analyzed data from the month of August since the summertime has ideal conditions for outdoor biking.

## Results

Our analysis yielded several insights that helped us to better understand our prospects in Des Moines. The first is straightforward proof-of concept, in which we analyzed the number of rides by the hour of the rides' start time:
<img width="1193" alt="image" src="https://user-images.githubusercontent.com/99628051/170900523-874f0857-bd29-4e53-986d-12255e259a41.png">
There is absolutely a critical mass of users who are taking advantage of bikesharing during commute hours, especially the evening commute (5-7PM). This usage data also suggests a possible maintenance window during the lowest usage hours, from approximately 2AM-5AM.

Once we knew our users were likely to need the service, we needed to establish certain basic usage patterns. Foremost among these was the ride duration:
<img width="1165" alt="image" src="https://user-images.githubusercontent.com/99628051/170900682-9b878ed9-d822-4c4c-8878-8696f89005f2.png">
Clearly riders are tending to use the service for durations mostly not in excess of 30 minutes. This is very helpful for thinking about possible marketing strategies, promotions, and even UX/UI considerations (less need for long-term reminders like, say, parking apps would require).

Outside of the weekly commute, there is also a proven use case for weekenders, as demonstrated by the heat map below:
<img width="915" alt="image" src="https://user-images.githubusercontent.com/99628051/170901097-d26ae47d-16e5-4228-a7f4-65eac5802726.png">
Although the "hottest" parts of the map are during the weekday morning and (especially) evening commutes, there are also comparatively hot zones on both weekend days, which we will explore further once we add another dimension to our analysis. But first, we need to address an elephant in the room of our data:

<img width="1140" alt="image" src="https://user-images.githubusercontent.com/99628051/170901218-ed7bbe10-ecf6-4e45-a6f9-66182951abd2.png">
Simply put, we have far more male users than female users; moreover, we have only been collecting data according to this strict gender binary, which could have an impact on our results in urban areas which may have a nontrivial contingent of gender-nonconforming clientele. This raises some important questions about our prior analysis: are usage patterns homogeneous across gender? Let us repeat some of our earlier analyses in order to confirm:

<img width="1181" alt="image" src="https://user-images.githubusercontent.com/99628051/170901462-4431b047-4035-427b-b06c-60c25fe3850c.png">
Our conclusion about shorter rides still seems to hold across the gender breakdown.

<img width="1185" alt="image" src="https://user-images.githubusercontent.com/99628051/170901524-db5ea33f-af25-4012-b952-de9ec6ba43a8.png">
The commute and our "weekend hotspots" also seem consistent across gender.

One last dimension according to which it might make sense to rethink our data is the distinction between "subscriber" and "customer" (someone who pays for recurrent usage of the service versus someone who pays separately each time). This gives us an interesting insight:
<img width="1127" alt="image" src="https://user-images.githubusercontent.com/99628051/170901713-4dc056fb-5e74-433e-b826-c5206770f521.png">
As we start our program in Des Moines, it may behoove us to think about "weekender" packages, or maybe other avenues for converting customers into subscribers.

## Summary

In summary, the New York City data gives us every reason to believe that Des Moines customers would have a similar need for a bikesharing service. Whether it be to accommodate weekday commutes or weekend recreation, the demonstrated need is clear enough from the NYC data to warrant a program in a smaller-but-active city like Des Moines. The NYC data also pose some important questions that the Des Moines program, in its incipience, could be in a unique position to answer: for example, what would happen if we gathered data on customers with additional gender identities beyond the male/female binary? Moreover, there is a not-insignificant presence of colleges/universities in both NYC and Des Moines; selecting August as the month of analysis means possibly losing data on college/university students from both cities, so looking at the same patterning in a month like September or October could be illuminating in terms of whether we see an effect on the data based on how many college students take advantage of bikesharing.
