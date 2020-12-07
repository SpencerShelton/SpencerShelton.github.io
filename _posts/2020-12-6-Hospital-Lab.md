---
layout: post
title: Hospital Lab
---
**Results**  
Most Beds Per Person in County: New York (0.007143 beds per person)  

Beds Per Person in Each County Arragned Most to Least (Rounded to 6 dicimal places):    
`new york: 0.007143`  
`warren: 0.006708`  
`albany: 0.004864`  
`chemung: 0.004731`  
`otsego: 0.004181`  
`broome: 0.004023`  
`clinton: 0.003952`  
`onondaga: 0.0039`  
`ontario: 0.003891`  
`rockland: 0.003717`  
`schenectady: 0.003698`  
`franklin: 0.003643`  
`cortland: 0.0036`  
`nassau: 0.003524`  
`westchester: 0.0035`  
`oneida: 0.00334`  
`erie: 0.003301`  
`columbia: 0.003269`  
`chautauqua: 0.003248`  
`cattaraugus: 0.003172`  
`niagara: 0.00308`  
`jefferson: 0.002951`  
`monroe: 0.002939`  
`st. lawrence: 0.002879`  
`bronx: 0.002811`  
`montgomery: 0.002788`  
`richmond: 0.002733`  
`rensselaer: 0.002722`  
`orange: 0.002586`  
`suffolk: 0.00258`  
`kings: 0.002461`  
`dutchess: 0.002459`  
`genesee: 0.002409`  
`steuben: 0.002276`  
`sullivan: 0.00223`  
`tompkins: 0.002184`  
`ulster: 0.001804`  
`madison: 0.001756`  
`putnam: 0.001749`  
`queens: 0.001651`  
`wyoming: 0.001639`  
`allegany: 0.001603`  
`fulton: 0.00152`  
`delaware: 0.001458`  
`cayuga: 0.001443`  
`wayne: 0.0014`  
`oswego: 0.001385`  
`schuyler: 0.00138`  
`chenango: 0.001333`  
`schoharie: 0.001265`  
`saratoga: 0.001227`  
`lewis: 0.001155`  
`essex: 0.001046`  
`livingston: 0.001041`  
`yates: 0.000997`  
`orleans: 0.000938`  
`herkimer: 0.000397`  
`greene: 0.0`  
`hamilton: 0.0`  
`seneca: 0.0`  
`tioga: 0.0`  
`washington: 0.0`  

**Method**:  
To complete this code I began by drawing from the work I had done to complete the Intro to APIs exercise. I slightly modified the code to make it a bit more general and used it as a part of a file I called Read that I imported into a program I used to take data from the API and I used a file I made called Write write it to a csv file. I then used my code from our cleaning classwork in a file called Clean and a file called Analize to make the text lowercase and flag any values that seemed to be very different from the other values and used Write to write the cleaned data to a new csv file and the flagged values to a text file. Next, I visually inspected my cleaned data and flagged values for any potentially erroneous data. I then used a file called HospitalAnalize that imported Read, Analize, and Write to calculate the number of beds in each county and arrange the county from most beds to least beds and had the program write out the data to a csv and a text file. In this lab I did my bdest to foucus alot on the reusibility of the code. All of my Hospital files are specialized to this assignment but my Read, Write, Clean, and Analize files I wrote to be more general so that I can apply them to future projects.
