---
title: Insert title here
key: 7cd445d00011c3bbcbfdf671e32f0caa
video_link:
  mp3: http://assets.datacamp.com/production/repositories/3835/datasets/6505bcfe1fadf25b748950782436b180eb359040/dates.mp3

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



---
## Warehouse Inventory

```yaml
type: "FullImageSlide"
key: "fee0a68c96"
```

`@part1`
![Table of Data](http://assets.datacamp.com/production/repositories/3835/datasets/dc08a0e8ba4bdb5e6e01ab60323783138b2f0ba1/table_of_data.png)


`@script`
We have a table of data here and it represents a warehouse in the back of this shop. It’s all the same item, but they have a specific SKU based on the date on which they were manufactured. You just found out that everything produced in the last week needs to be sent back. We’re going to do some formatting to point out which items those are that were made in the last week but, before we do that, there’s a couple of setup items that we need to be aware of.


---
## "Today's" Date

```yaml
type: "FullCodeSlide"
key: "4647993e0e"
```

`@part1`
"Today's" Date

`=TODAY()`

10/20/2018


`@script`
The first thing is today’s date. Some of these actions that we are going to do are dynamic because of what the date is. It is helpful to know that today is October 20, 2018.


---
## Country Specific

```yaml
type: "FullSlide"
key: "8aa1517904"
```

`@part1`
Month, Day, Year

MM/DD/YYYY


`@script`
The next thing that you probably noticed by now is that I’m in a country that is showing the month first, and then the day, and then the year. You might not be. Just make sure yours is right for the way you want to work on it.


---
## Localization settings

```yaml
type: "FullImageSlide"
key: "77cb9baa5f"
```

`@part1`
![settings](http://assets.datacamp.com/production/repositories/3835/datasets/eb9a03602c1ed202aed2b82a8a4409a895d903a2/settings.png)


`@script`
Go to file, spreadsheet settings and make sure the locale is correct.


---
## United States

```yaml
type: "FullImageSlide"
key: "97fe97d322"
```

`@part1`
![United States](http://assets.datacamp.com/production/repositories/3835/datasets/620c9c0b109e1fad40f0cf24fc39220268e79111/united_states.png)


`@script`
Mine is the United States. If that’s not correct, change it there. Then, you can work with the dates in a way that makes sense to you.


---
## Highlight Your Dates

```yaml
type: "FullSlide"
key: "ddb2305838"
```

`@part1`
![Highlight the Dates](http://assets.datacamp.com/production/repositories/3835/datasets/92fe84bed06fa357ed08c6dcc327f439a36d60f5/highlight_dates.png)


`@script`
The first thing that I would do I highlight the dates that you want to work on. I would just highlight the dates. I wouldn’t highlight any of the other columns because Google Sheets might think that these are dates too. Then, start your conditional formatting.


---
## Within the Last Week

```yaml
type: "FullImageSlide"
key: "97ac571745"
```

`@part1`
![Within the Last Week](http://assets.datacamp.com/production/repositories/3835/datasets/1b65ac609ff851068e1df6c60c3b1adad3bdcf75/date_is.png)


`@script`
Go back to Format left click on Conditional Formatting. You’ll get your little dashboard here on the right. You can see that the range is right. You could’ve just typed it in there but it usually easier to pick it up with your mouse. There’s three options here that are aware of what the date today is. All three of these are going to operate differently tomorrow and they will have operated differently yesterday. 

I am going to use Date is. What I am actually looking for is all of the items that were made in the last week.


---
## Date is Before

```yaml
type: "FullImageSlide"
key: "22f63169d5"
```

`@part1`
![Date is Before](http://assets.datacamp.com/production/repositories/3835/datasets/8dd515f8e1e28a012fbbdc0489d0f1f3432aad6e/date_is_before.png)


`@script`
At first, I would think that I want to look at Date is before. But, be careful.


---
## Result showing last week's items

```yaml
type: "FullImageSlide"
key: "40bd134c38"
```

`@part1`
![Date Is](http://assets.datacamp.com/production/repositories/3835/datasets/a86080f1430258f987b98576254a8cc440409100/before_past_week.png)


`@script`
If you do Date is before, some of these options look like they’re going to do the past week, but what that will do is that is that it is going to go before the past week. If you were to choose that, it’s picking up 10/8 and 10/9.  Those are more than a week back. That’s not what you want.


---
## Date Is

```yaml
type: "FullImageSlide"
key: "e1655ff594"
```

`@part1`
![Date Is](http://assets.datacamp.com/production/repositories/3835/datasets/1b65ac609ff851068e1df6c60c3b1adad3bdcf75/date_is.png)


`@script`



---
## Result Showing in the Past Week

```yaml
type: "FullImageSlide"
key: "0ad552a2b2"
```

`@part1`
![In the Past Week](http://assets.datacamp.com/production/repositories/3835/datasets/20c1e777f52fe4e97daf5fab2076b4588ec54e1c/in_the_past_weeek.png)


`@script`
Use the Date is function. In here, use the Past week. That is going to pick up seven items. That’s what you want. This is the last seven days including today. 

So, there you have the list. You can print this out on a color printer and go back to the warehouse and pull these out because you are going to send them back to the vendor.


---
## Let's Practice!

```yaml
type: "FinalSlide"
key: "d180471a53"
```

`@script`


