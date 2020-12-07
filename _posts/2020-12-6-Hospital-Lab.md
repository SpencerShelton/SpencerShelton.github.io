---
layout: post
title: Hospital Lab
---
**Results**  
Most Beds in County: New York (11813 beds)  

Beds Per County Arragned Most to Least:    
`new york: 11813`  
`kings: 6484`  
`nassau: 4804`  
`bronx: 4092`  
`suffolk: 3864`  
`queens: 3863`  
`westchester: 3414`  
`erie: 3050`  
`monroe: 2200`  
`onondaga: 1824`  
`albany: 1501`  
`richmond: 1301`  
`rockland: 1208`  
`orange: 978`  
`broome: 789`  
`oneida: 776`  
`dutchess: 727`  
`niagara: 655`  
`schenectady: 574`  
`rensselaer: 435`  
`warren: 434`  
`ontario: 426`  
`chautauqua: 425`  
`chemung: 411`  
`jefferson: 344`  
`ulster: 325`  
`clinton: 321`  
`st. lawrence: 319`  
`saratoga: 278`  
`otsego: 254`  
`cattaraugus: 248`  
`tompkins: 228`  
`steuben: 222`  
`columbia: 201`  
`franklin: 186`  
`putnam: 174`  
`cortland: 174`  
`sullivan: 169`  
`oswego: 166`  
`genesee: 141`  
`montgomery: 138`  
`wayne: 128`  
`madison: 126`  
`cayuga: 113`  
`fulton: 82`  
`allegany: 76`  
`livingston: 67`  
`delaware: 67`  
`wyoming: 67`  
`chenango: 65`  
`essex: 40`  
`schoharie: 40`  
`orleans: 39`  
`lewis: 31`  
`herkimer: 25`  
`yates: 25`  
`schuyler: 25`  
`greene: 0`  
`hamilton: 0`  
`seneca: 0`  
`tioga: 0`  
`washington: 0`  

**Method**:  
To complete this code I began by drawing from the work I had done to complete the Intro to APIs exercise. I slightly modified the code to make it a bit more general and used it as a part of a file I called Read that I imported into a program I used to take data from the API and I used a file I made called Write write it to a csv file. I then used my code from our cleaning classwork in a file called Clean and a file called Analize to make the text lowercase and flag any values that seemed to be very different from the other values and used Write to write the cleaned data to a new csv file and the flagged values to a text file. Next, I visually inspected my cleaned data and flagged values for any potentially erroneous data. I then used a file called HospitalAnalize that imported Read, Analize, and Write to calculate the number of beds in each county and arrange the county from most beds to least beds and had the program write out the data to a csv and a text file. In this lab I did my bdest to foucus alot on the reusibility of the code. All of my Hospital files are specialized to this assignment but my Read, Write, Clean, and Analize files I wrote to be more general so that I can apply them to future projects.
