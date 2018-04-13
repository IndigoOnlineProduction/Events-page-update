# Updating the Indigo Events Page
```
https://preview.indigo.ca/en-ca/events/listings/
```

## Content Block ID:
```
29936
```

## The Events Team will usually provide the following information
![Image of Events Info](https://raw.githubusercontent.com/IndigoOnlineProduction/Events-page-update/master/Events%20Info.jpg)

### This information corresponds to:
```
1) The Type of Event
2) & 3) The Featured Subject
4) The Featured product
5) The product URL
6) The product SKU
7) The Date & Time of the Event
8) The Store Number at which the event is taking place
9) The corresponding Facebook event URL
```

### Find a similar event within the content block and copy in the information:
![Image of Events HTML block](https://static.indigoimages.ca/assetsexternal/events-html.jpg)

### If the event features multiple authors/book covers/dates, simply copy the relevant sections/elements and paste in the necessary information

### If the Event Info includes a list i.e.
```
Open Mic Guidelines:
- Local artist sign-up sheet will be available in store starting at 9am on the day of the event
- Each artist will have 2-3 minutes onstage
```
### Use this format and copy it within the "eventInfo" div below the last p tag
```
<strong>Open Mic Guidelines:</strong>
          <ul>
            <li>Local artist sign-up sheet will be available in store starting at 9am on the day of the event</li>
            <li>Each artist will have 2-3 minutes onstage</li>
          </ul>                  
```

### If the Event Info requires a button, e.g. "Buy Tickets" use this format and copy within the "eventInfo" div below the last element (likely a paragraph or list):
```
<p><a href="http://www.thebabyshows.com/toronto/spring/visitors/buy-tickets" target="_blank" class="allButton">buy tickets</a></p>
```

### Once the event has been updated, check in the changes then check all links for accuracy and ensure that the event is linking to the correct host store

### Send off to the Events team and give yourself a pat on the back!
