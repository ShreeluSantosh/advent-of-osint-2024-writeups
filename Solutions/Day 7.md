# Day 7

## Challenge

Did you know there's an Earth Day flag? Surprisingly, the image that appears on this flag is world-famous; however, the photographer’s identity remains uncertain.

A man decided, as a personal challenge, to find an answer to this question and created a website dedicated to this research.

> The identity of the photographer is unverifiable? I decided to take that as a personal challenge.

When was the last revision of his website (format YYYYMMDD)?

Answer format: 20220816

## My Methodology

- After a bit of Googling about the Earth Day flag, I found that famous photo is called *The Blue Marble*, and that it was taken during Apollo 17 mission.
  ![Screenshot 2024-12-07 184401](https://github.com/user-attachments/assets/f82c0814-d09a-4835-80cd-e4fc58d3d89b)
- Another hint in the challenge is the quote "The identity of the photographer is unverifiable? I decided to take that as a personal challenge.". So I used it as a Google search keyword, and found two results:
  ![Screenshot 2024-12-07 184113](https://github.com/user-attachments/assets/beed6b24-0736-49e5-b5a5-9b352bcdd40c)
- The first result took me to this site:
  ![Screenshot 2024-12-07 184330](https://github.com/user-attachments/assets/1a30388a-c653-4ce8-ad29-eadecee17a47)
- I suspected that the hyperlink 'InfoDabble' could be the website I was looking for. But on clicking it, it took me to www.ehartwall.com/lander, which appears to be unavailable.
- I went to Wayward Machine (web.archive.org), and found that the domain is up for sale via GoDaddy. I went to the list of captures of the website, and went to the snapshot at 2012 January 28, at 21:55:14.
  ![Screenshot 2024-12-08 174529](https://github.com/user-attachments/assets/b47cbbb6-fdc0-4508-a50f-176e3b3f1592)
- The last updated date is given, which is the answer to the first question. The second question appears:
  ```
  To support his theory, Eric Hartwell relies on the radio exchanges of the astronauts.

  When it was too late to take more photographs, Ronald mentioned the value displayed on the camera’s image counter.

  How many photos were taken?
  Answer format: 284
  ```
- I went to this capture: https://web.archive.org/web/20120128215514/http://www.ehartwell.com/Apollo17 and found this transcript of the radio exchange:
  ```
  004:59  Cernan: "I know we're not the first to discover this - but we'd like to confirm, from the crew of America, that the world is round."
  CapCom: "Roger. That's a good data point."
  CapCom: "Have you gotten a good look at any of that weather down there on the Antarctic?"
  Cernan: "Well, Ron's at window number 1 - maybe he can tell you a little about it."
  Evans: "You know, it's real funny there in Antarctica the - You can see the snow, but there isn't any weather at all in it. All of the weather's around it in the water."
  Schmitt: "That's where the moisture is."
  Schmitt?Evans? "I don't know what to take a picture of."
  
  Both Evans and Schmitt are looking at the Earth through their side windows. Schmitt takes a series of Earth photos (#110 AS17-148-22717 through #115 AS17-148-22722) with varying exposures, using the telephoto lens.
  ...
  
  005:02: Cernan?Schmitt? "No, I'll change lens now."
  
  They change the lens from 250mm telephoto to 80mm normal in preparation for the S-IVB burn. While changing the lens, they bump the shutter causing the blank frame (#118, AS17-148-22724). Cernan takes the photo of the S-IVB (#118, AS17-148-22724) through the hatch window.
  Cernan?Evans? "Okay. Here Jack, can you see it good?"
  Schmitt?Evans?Cernan? "Check the lens[settings] now. I took an F-22 stop."
  
  Cernan: "Okay. Here Jack, can you see it good?"
  Schmitt: "Check the lens[settings] now. I took an F-22 stop."
  Cernan passes the camera to Schmitt so he can photograph the whole Earth with the normal lens. Schmitt takes the first picture (frame #119, AS17-148-22725) then remembers to change the f-stop to compensate for the brightness of the Earth. Schmitt then takes three more photos, with slightly different aim because there's no viewfinder and he wants to make sure to get the whole planet in the picture. These photos are the famous "Blue Marble".
  Schmitt passes the camera back to Cernan for pictures of the S-IVB burn through the hatch window. Schmitt reminds Cernan he changed the lens setting.
   
  Cernan: "Okay. Here Jack, can you see it good?"
  Cernam: "Check the lens[settings] now. I took an F-22 stop."
  Cernan passes the camera to Schmitt so he can photograph the whole Earth with the normal lens. Schmitt takes the first picture (frame #119, AS17-148-22725) then Cernan reminds him to change the f-stop to compensate for the brightness of the Earth. Schmitt then takes three more photos, with slightly different aim because there's no viewfinder and he wants to make sure to get the whole planet in the picture. These photos are  the famous "Blue Marble".
  
  Cernan: "There it goes, Bob."
  Schmitt? "There it goes, finally."
  
  S-IVB evasive burn starts (no photo)
  Schmitt? "It's going to be gone, I think, before we -"
  Evans? "Houston, Magazine, November, November is on about 123 right now."
  
  Cernan didn't get a photo of the S-IVB through the hatch window. He passes the camera to Evans so he can take a parting shot through window 1, but it's too late.
  Evans reports the frame count. [Note: Frame count is +-1 due to the analog frame counter] .
  ```
- The last photo number is 123, but given that the frame count is +/- 1, so the answer could be 122 or 124.
- 124 turned out to be the answer.

## Reward
![Screenshot 2024-12-08 175548](https://github.com/user-attachments/assets/0304acfd-42e9-4072-9771-ee154cd2003a)
