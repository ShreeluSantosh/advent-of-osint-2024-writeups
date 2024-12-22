# Day 18

## Challenge

Callisto, also known as BlueCharlie, COLDRIVER, GOSSAMER BEAR, Reuse Team, SEABORGIUM, Star Blizzard, TA446, is a suspected Russian cyber threat actor believed to have been active since at least 2017  Callisto.

According to open-source reports, some domains registered by the Callisto group can be linked to other domains using their Whois records.

The website live-login.info was registered nine years ago, and traces of it can be found using sites that offer « whois history ».

Other domains were registered with the same email, including one created in January 2016, leading to a steroids site. This site is now offline.

What was this domain name?

Answer format: microsoft.com

## Methodolgy (from official video solution)

- First of all, we need to look up the history of the domain, so this is one website which allows us to look up the history of a domain - whoxy
  ![image](https://github.com/user-attachments/assets/07402aa1-dd4c-436e-92a4-d9f6db8277ea)
- On entering the domain name, and then going to its history, I found this:
  ![image](https://github.com/user-attachments/assets/908157db-b27e-418d-ae02-cc0891c292a6)
- The email address is: vladimirdj90@gmail.com
- There are 12 domains associated with this email address:
  ![image](https://github.com/user-attachments/assets/1c35a544-375d-44dd-9ce6-45ed26388cfa)
- As per the challenge, the domain in question leads to a steroids site. So, among the domains, mymuscle.org appears to fit the description, as well as the creation date.
- Second question:
  ```
  At the time, the website http://mymuscle.org had a page on the Russian social network VK.
  What is the date of birth (format YYYYMMDD) of this page's administrator?
  Answer format: 20121228
  ```
- I went to Wayback Machine (web.archive.org), and entered http://mymuscle.org, and chose a timestamop in October 2016 (when the site was up). Then, scrolling to the bottom of the page, I found a logo VK
  ![image](https://github.com/user-attachments/assets/252d6c2a-0950-46a3-b4f8-cf8775971b6a)
- On the right hand pane, I found Contact box, with 2 members' names.
  ![image](https://github.com/user-attachments/assets/ceec2933-de72-4827-a67a-bf14f2b82aa7)
- On clicking the person with name 'Valera Brejnev', I got redirected to the profile page:
  ![image](https://github.com/user-attachments/assets/3593ec9e-bd64-4161-8873-e6c614bec48a)
- On clicking Learn More link, I got a popup box, where their birthdate is present - September 7, 1979

## Reward

![image](https://github.com/user-attachments/assets/a9e654cb-918c-4984-9321-0b60ca299b50)
