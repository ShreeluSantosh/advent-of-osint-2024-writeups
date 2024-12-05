# Day 4

## Challenge

In France, among its various missions, the "Cour des comptes" 
oversees the accuracy of the accounts of companies receiving donations.

In this context, it has repeatedly examined the finances of the organization managing "Téléthon" funds.

In its oldest report on the matter, the Cour raised concerns 
regarding "organismes relais" or "associations relais" (intermediary 
organizations or associations) and noted that "la tendance [...] s'est 
accentuée" (the trend [...] has intensified).

Based on the report 
data, give the initial value, the final value and calculate by how much 
this trend has increased as a percentage.

Answer format: 62% 53% 48%

Warning: do not use the English language site of "Cour des comptes", it is not functional. If you use this site, use an automatic translation tool (such as Google) on the French pages.

## My Methodology

- I went to Google search to search for Cour des comptes, and found this official website: https://www.ccomptes.fr
  ![Screenshot 2024-12-05 180957](https://github.com/user-attachments/assets/de524f2d-fac4-4b82-afd2-621fd3ecc8d2)
- However, on trying to open the URL, I was met with ‘Unable to connect’ error for this website. It was only after using a VPN (to Japan) that I was able to view the website
- Once in the website, I clicked on the search icon in the top right corner, and entered ‘Téléthon’. I got a long list of results
  ![Screenshot 2024-12-05 181152](https://github.com/user-attachments/assets/e74c2ff6-b2d1-42a7-9c98-1cf7e66a62ba)
- Since the ‘oldest report’ was mentioned in the challenge, I decided to look for the oldest report available, and found one titled, ‘Association française contre les myopathies (AFM)’, that was from 1996
  ![Screenshot 2024-12-05 181206](https://github.com/user-attachments/assets/c407b77a-331f-41d8-ba03-811e1345a2a9)
- After opening the PDF, I used the browser find feature to search for words ‘la tendance’, and found one match within paragraph below:
  ![Screenshot 2024-12-05 181419](https://github.com/user-attachments/assets/3060512d-9ef2-47e4-8c48-aeb2e56e1948)
- I used Google Translate to translate the paragraph for ease of understanding
- Translated:
    
    `The researcher is also invited to provide in a separate document the references of the account to be credited which may be that of a research organization or that of an association relay. `

    `In 1988, a survey carried out by IGAS revealed that 40% only 100 of AFM grants were paid to the researcher's employing organization. For the year 1993, and on the basis of the information communicated by the AFM, the Court's rapporteurs assessed this percentage from a sample of files representing approximately 80 p. 100 of the amount subsidies, which, even if these files are unequally distributed, allows for a generalization.`

    `The table below shows that the trend observed in 1988 has become more pronounced, since 34 p. Only 100% of funds are now paid to the organizations to which the teams. It is more marked at INSERM, where the accounting officer only receives around 17 p. 100% of the funds intended for its researchers, while this percentage is 48%. 100 for the CNRS.`
    
- After a day of scrambling my head for various combinations of values from the above snippet, I took a hint from the video solution
- From the second paragraph, percentages were given for years 1988 and 1993 - 40% and 34%
- So, calculating the difference % should be like this:
    
    $diff. percentage = [(final - initial)/initial]$  x  $100$
    
    $diff.percentage = [34-40/40] * 100 = [-6/40]*100 = -15$
    
- So, the answer would be 34% 40% 15% (ignoring the minus sign as it was not asked in the answer format)

- ## Reward
- ![Screenshot 2024-12-05 182137](https://github.com/user-attachments/assets/7af53592-44f3-4dd2-8df3-8bc80a5354eb)

  
