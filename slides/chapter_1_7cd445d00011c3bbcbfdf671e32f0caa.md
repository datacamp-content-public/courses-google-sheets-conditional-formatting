---
title: Insert title here
key: 7cd445d00011c3bbcbfdf671e32f0caa
video_link:
  mp3: http://assets.datacamp.com/production/repositories/3835/datasets/09cbe83bfc87c5ee6aa20f7a2be4b18a29ac7c46/warehouse_inv.mp3

---
## Conditional Formatting with Today's Date

```yaml
type: "TitleSlide"
key: "6a6b3b44c2"
```

`@lower_third`

name: Adam Steinfurth
title: Instructor


`@script`
Now we are going to go over Conditional Formatting using relative dates. Sheets has some built in functionality for formatting dates relative to the current date on which you're using the spreadsheet.


---
## "Today's" Date

```yaml
type: "FullCodeSlide"
key: "4647993e0e"
center_content: true
```

`@part1`
10/27/2018{{1}}


`@script`
It is important to know that "today"’s date, which is the date on which these slides were made, is October 27, 2018. The date of today will be different for you because the functions that we will be reviewing are aware of the current date.


---
## Country Specific

```yaml
type: "FullSlide"
key: "8aa1517904"
center_content: true
```

`@part1`
Month, Day, Year{{1}}

MM/DD/YYYY{{2}}


`@script`
I’m in a country that is showing the month first, and then the day, and then the year. You might not be. Just make sure yours is right for the way you want to work on it.


---
## Localization settings

```yaml
type: "FullImageSlide"
key: "77cb9baa5f"
center_content: true
```

`@part1`
![settings](http://assets.datacamp.com/production/repositories/3835/datasets/a4aa1ba645f62f2ec6c81f324a671cece7dd2e9b/settings.png)


`@script`
If you need to adjust your locality, go to File, Spreadsheet settings, and this is where you can change it.


---
## United States

```yaml
type: "FullImageSlide"
key: "97fe97d322"
center_content: true
```

`@part1`
![United States](http://assets.datacamp.com/production/repositories/3835/datasets/3aafa75a83da3a48cff1378f1ef1e9374a18c49d/united_states.png)


`@script`
Mine is the United States. If that’s not correct for you, change it here if you need to. Then, you can work with the dates in a way that makes sense to you.


---
## Warehouse Inventory

```yaml
type: "FullImageSlide"
key: "fee0a68c96"
center_content: true
```

`@part1`
![Table of Data](http://assets.datacamp.com/production/repositories/3835/datasets/c7bf774787be24ff420ae9ae73089d8d133f2a5f/table_of_data.png)


`@script`
Our example is a table of data that represents a warehouse in the back of a shop. Every line is the same item except that they have each unique SKU based on the date on which they were manufactured. You just found out that everything manufactured in the last week needs to be sent back. We’re going to do some formatting to point out which items are the ones that were made in the last week.


---
## Highlight Your Dates

```yaml
type: "FullSlide"
key: "ddb2305838"
center_content: true
```

`@part1`
![Highlight the Dates](http://assets.datacamp.com/production/repositories/3835/datasets/b802bb466d0ababa9210b8086dc7e3ec31f581ea/highlight_dates.png)


`@script`
The first thing that you want to do is highlight the dates that you want to work on. I would just highlight the column with the dates. I wouldn’t highlight any of the other columns because Google Sheets might think that those other values are dates too. Once you have the dates selected, then you can start your conditional formatting.


---
## Conditional Formatting Menu Option

```yaml
type: "FullImageSlide"
key: "277558f41a"
```

`@part1`
![Menu](http://assets.datacamp.com/production/repositories/3835/datasets/97528a114356007cc9e67c967fdf0045f6f6f939/menu.png)


`@script`
You would go up to Format on the menu and then select Conditional Formatting from there.


---
## Date is Before

```yaml
type: "FullImageSlide"
key: "22f63169d5"
center_content: true
```

`@part1`
![Date is Before](http://assets.datacamp.com/production/repositories/3835/datasets/5d681344d3e0f186adfef59ce03859d92274f279/date_is_before.png)


`@script`
You’ll get this little dashboard that you see on the right. 

There’s three options there and they all pertain to today's date. All three of these are going to operate differently tomorrow and they will have operated differently yesterday as well.

At first, you may think that you want use Date is before. But, if you do Date is before, it picks a point and time and highlights everything before that. That’s not what you want.


---
## Date Is

```yaml
type: "FullImageSlide"
key: "97ac571745"
center_content: true
```

`@part1`
![Within the Last Week](http://assets.datacamp.com/production/repositories/3835/datasets/83042cc50b673942acde155aea5e065104bd9171/date_is.png)


`@script`
Use the Date is choice on the menu instead.

This will let me choose a range of dates that are relative to today's date.


---
## In the Past Week

```yaml
type: "FullImageSlide"
key: "ca2b3705c4"
center_content: true
```

`@part1`
![In the Past Week](http://assets.datacamp.com/production/repositories/3835/datasets/f56e02afe971b018e114cf77eece9843663b9497/in_the_past_week_menu.png)


`@script`
In the next box after you click Date is, you want to use the Past week in order to get the last seven days. Choose the Past week and click done.


---
## Result Showing in the Past Week

```yaml
type: "FullImageSlide"
key: "0ad552a2b2"
center_content: true
```

`@part1`
![In the Past Week](http://assets.datacamp.com/production/repositories/3835/datasets/315b7c7287893c8327d0dd3f4c3fc9dfe9dce0ad/in_the_past_week.png)


`@script`
So that's it. That's what we've been trying to do with conditional formatting. We've gone in and we've highlighted all of the items that were manufactured in the last seven days. You can just print out this list, bring it out to your warehouse, and pull those items out.


---
## Let's Practice!

```yaml
type: "FinalSlide"
key: "d180471a53"
```

`@script`
That should cover the date options that are relative to a specific day. In our next lesson, we'll cover date options that let you specify specific dates no matter what date it is right now.

