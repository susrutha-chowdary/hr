# A dashboard to analyse a company's employees attendance records
## Description:
``` The dataset is an Excel workbook that contains employees attendance data of a company for 3 months in different worksheets. The main reason for this dashbord id to find out some insights into employees trends like: 
- what is the working prefrence of an employee? {work from home or office}
- which days of the week are more popular for work from home to working from office?
- find out the percentage of sick leave. If it is >10% then, Is it an indication of some viral disease like flu or covid 19?
- Is there any trend we can find?
```

## Problem areas:

The workbook contains data in 3 different workshets with dates as the columns. In order to proceed with the analysis on the whole dataset we needed to append all the data into a single table. But the column names are different. Here is the blog that came to my help: [click here](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbkJaa0xvZ3h2SlN6U2RqUHo3QmdDVUJfckdQd3xBQ3Jtc0tsU0l6NzJPbDFBN1FEdTgxM0JLYlYyZVFhWXA2bkRxYzFyOWlUSW1UU2trZFo0Y2VSbVJVSWx4dVQzQXVIZ2R1X3FrOUQ0UFhrSkxXTS1YTXBtT2plaUVXZVJ2UnN3Vnl1TDd5M3VreHpmdjRtNlNoZw&q=https%3A%2F%2Fblog.crossjoin.co.uk%2F2018%2F07%2F09%2Fpower-bi-combine-multiple-excel-worksheets%2F&v=DwgC72_s-T4)
## Here is the image of the final dashboard:
![image](https://user-images.githubusercontent.com/87435569/189492881-a23c3811-dad0-476a-a4be-9791dbbe1a57.png)

## Inferences:
```
- The total work from home employee percentage over 3 moths is 10%. 
   Which means on an average we can find 10 employees working form home on any given day.
- The sick leave percent is not abnormal so there is no need to worry about any viral disease.
- From the charts we can find the present % is declining towards june while sick leave % is slightly increasing.
- We can infer that highest percentage if attendance is recorded on mondays and tuesdays.{Towards the starting of the week}
- We can also infer that most people are working from home(WFH) on fridays and thursdays.{Towards the end of the week} 
```
## Personalisation:
```
- Can create an automatic email notifiction when the present % is below 80% or sick leave % is above 10%.
- Can explore more on other leaves like festiveal leave, paid leave, birthday leave etc.
```
