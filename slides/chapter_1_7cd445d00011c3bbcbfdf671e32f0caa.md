---
title: Insert title here
key: 7cd445d00011c3bbcbfdf671e32f0caa

---
## Conditional Formatting with Dates

```yaml
type: "TitleSlide"
key: "6a6b3b44c2"
```

`@lower_third`

name: Adam Steinfurth
title: Instructor


`@script`
We have a table of data here and it represents a warehouse in the back of this shop. It’s all the same item, but they have a specific SKU based on the date on which they were manufactured. You just found out that everything produced in the last week needs to be sent back. We’re going to do some formatting to point out which items those are that were made in the last week but, before we do that, there’s a couple of setup items that we need to be aware of. The first thing is today’s date. Some of these actions that we are going to do are dynamic because of what the date is. It is helpful to know that today is October 20, 2018. The next thing that you probably noticed by now is that I’m in a country that is showing the month first, and then the day, and then the year. You might not be. Just make sure yours is right for the way you want to work on it. Go to file, spreadsheet settings and make sure the locale is correct. Mine is the United States. If that’s not correct, change it there. Then, you can work with the dates in a way that makes sense to you.  

The first thing that I would do I highlight the dates that you want to work on. I would just highlight the dates. I wouldn’t highlight any of the other columns because Google Sheets might think that these are dates too. Then, start you conditional formatting. Go back to Format left click on Conditional Formatting. You’ll get your little dashboard here on the right. You can see that the range is right. You could’ve just typed it in there but it usually easier to pick it up with your mouse. There’s three options here that are aware of what the date today is. All three of these are going to operate differently tomorrow and they will have operated differently yesterday. 

I am going to use Date is. What I am actually looking for is all of the items that were made in the last week. At first, I would think that I want to look at Date is before. But, be careful. If you do Date is before, some of these options look like they’re going to do the past week, but what that will do is that is that it is going to go before the past week. If you were to choose that, it’s picking up 10/8 and 10/9.  Those are more than a week back. That’s not what you want.

Use the Date is function. In here, use the Past week. That is going to pick up seven items. That’s what you want. This is the last seven days including today. 

So, there you have the list. You can print this out on a color printer and go back to the warehouse and pull these out because you are going to send them back to the vendor. 

But, if you’re thinking that you’re not sure that the items produced on 10/13 and 10/12 are going to be okay, so I kind of want to highlight those two. I’m going to think about whether I should return those, or maybe set them aside. 

Let’s highlight these dates again. Right now, it’s showing our current rule because we never clicked done. It’s important to do that. If you just start changing this, the old rule’s going to go away. If you left click Done first, this is where I want to add my new rule. 

Let’s make sure our range is correct. Let’s get E3:E16 again. We’re going to add a new rule.  It defaults to highlighting them all again. Let’s get rid of that. This is just looking for two dates that we know. We know we want to highlight 10/12 and 10/13. We’re going to skip the relative options here that work on the date. We’re going to dates between and let’s do the values. Just type in the dates, you don’t need quotes. 10/12/2018 and 10/13/2018. 

It just added them in green, but this is a different consideration. We’re not sure if we want to send them back so let’s not do green. Come down to the formatting style and let’s make this yellow because we’re tentative about it. And we’re going to select Done here and we’re going to left click out of this range. You’re done. 

You have all of the items in green that you know need to go back and you have the items in yellow that you need to consider. Hopefully that was helpful for understanding date formatting. The ranges and the way that you work with them are going to be different that regular numbers, but there are some good built in functions, as you saw, to deal with them.


---
## Localization settings

```yaml
type: "FullSlide"
key: "df8034a7b6"
```

`@part1`
- Check your settings

- Examples are MM/DD/YYYY


`@script`



---
## Valid Dates

```yaml
type: "FullSlide"
key: "ddb2305838"
```

`@part1`
Use the `DATEVALUE` function


`@script`



---
## Table of Data

```yaml
type: "FullCodeSlide"
key: "fb2ccf026d"
```

`@part1`



`@script`



---
## Conditional Formatting with Dates

```yaml
type: "FinalSlide"
key: "d180471a53"
```

`@script`


