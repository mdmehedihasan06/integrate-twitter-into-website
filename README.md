# Integrate Twitter into Website
This will help to get to know the easiest way of integrating twitter timeline into your website with dark and light mode and also in 6 different colors.
# Demo Page
### [See the demo for Twitter itself](https://plnkr.co/edit/Q7CKlCSsjk3WDCq8Aoqv?p=info)
## Just start integrating
You will just need to place an anchor tag with your desired account into a div and then twitter widget script reference to your page.

    <div>
    <a class="twitter-timeline" data-width="300" data-height="400" data-theme="dark" data-link-color="#2B7BB" href="https://twitter.com/twitter">Tweets by Twitter</a>
    <script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>
    </div>
    
## Customization
### Theme Mode
Light & Dark theme are supported for twitter widget.
For regular light theme you just need to set the first value into the anchor tag and for dark theme set the second value. 
```css
    data-theme="light"
    data-theme="dark"
```    
### Custom Color
These are the color set you can use to beautify your twitter feeds 
```css
   data-link-color="#F5F8FA"
   data-link-color="#9266CC"
   data-link-color="#19CF86"
   data-link-color="#FAB81E"
   data-link-color="#E95F28"
   data-link-color="#E81C4F"
   data-link-color="#2B7BB9"
```    
### Custom Height & Width
Just change the height and width values of the following attributes of the anchor tag and you will see the magic
```css
   data-width="300" data-height="400"
``` 
### Connect any Twitter Account
you can get any twitter account feeds in your own website just by changing the href property of the anchor tag. Just replace the url below with your own accound url or desired account url. 
```css
   href="https://twitter.com/twitter"
``` 
### That's it. You are all set to see the magic.

# Reference
You can visit the original twitter publish page to get more detailed view [here](https://publish.twitter.com)
