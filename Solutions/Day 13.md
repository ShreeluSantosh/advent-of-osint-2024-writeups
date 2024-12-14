# Day 13

## Challenge

Exactly 84 years ago today, the Republican evening newspaper of a major city in the south of France reported that an avalanche had occurred in the Alps a few days earlier.

What was the number of the national road that was cut off?

Answer format: 22

## My Methodology

- I first needed to look at a map of France (with cities, without satellite terrain). Below is from https://geology.com/world/france-satellite-image.shtml:
  ![image](https://github.com/user-attachments/assets/7f3e8b71-428a-4ca3-87a4-c464551356cd)
- Since the challenge mentioned 'a major city', my hypothesis is that 84 years ago (i.e. in 1940), newspapers often report incidents that occured nearby. Since a small part of the Alps is in France, I need to focus on cities near the mountains.
- Using the map of Alps (with national borders) from https://www.britannica.com/place/Alps, I determined the possible candidates are Lyon, Marseilles, Cannes, and Nice.
  ![image](https://github.com/user-attachments/assets/94bf05e5-a8a2-445a-8a10-b25a082895b7)
- For each city, I had to find the list of Republican newspapers. The fact that the challenge says that the report happened exact 84 years ago, means that the newspaper issue I'm looking for is December 13, 1940.
- Given the year - 1940, when France was under German occupation (since June 1940), I checked the maps of the areas under German occupation, and the areas where the Vichy goverment controlled.
- This is the map of areas under Vichy from https://www.britannica.com/event/Vichy-France
  ![image](https://github.com/user-attachments/assets/5e54e001-91d7-4d8d-a57b-18a575422359)
- Getting a list of newspapers from https://www.thepaperboy.com/france/newspapers/country.cfm and checking their founding dates, I narrowed down to Le Progrès
- Its Republican status is confirmed in French version of its Wikipedia page https://fr.wikipedia.org/wiki/Le_Progr%C3%A8s_(Lyon):
  ![image](https://github.com/user-attachments/assets/d1e3d4c1-5c7e-4f50-afce-a9d032932526)
- I went to its Archives at https://gallica.bnf.fr/ark:/12148/cb32843715j/date.item and looked for December 13, 1940 issue. But it didn't have the issues from that year.
- In end, I brute-forced the answer, starting from 100 downwards, till I got 91 as the answer

## Rewards
![image](https://github.com/user-attachments/assets/4c8d51a4-d12f-4880-a0df-e334f7cf2a23)
