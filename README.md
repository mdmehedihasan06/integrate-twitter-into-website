# Integrate Twitter into Website
This will help to get to know the easiest way of integrating twitter timeline into your website with dark and light mode and also in 6 different colors.
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
    
    data-theme="light"
    data-theme="dark"
    
### Custom Color
For regular color set 
```css
   <div style="height:30px; width:30px; background-color: #F5F8FA"></div>
```

    data-link-color="#F5F8FA"
For violet color set

    data-link-color="#9266CC"
