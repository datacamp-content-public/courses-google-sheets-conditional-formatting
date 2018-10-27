---
title: Insert title here
key: 7cd445d00011c3bbcbfdf671e32f0caa
video_link:
  mp3: http://assets.datacamp.com/production/repositories/3835/datasets/086d215ecbaefaffec54922d660336d7b0aee3ce/warehouse_inv.mp3

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
Now we are going to go over Conditional Formatting using relative dates. Sheets has some built in functionality for formatting dates relative the current date on which you're using the spreadsheet.


---
## Warehouse Inventory

```yaml
type: "FullImageSlide"
key: "fee0a68c96"
center_content: true
```

`@part1`
![Table of Data](http://assets.datacamp.com/production/repositories/3835/datasets/520c3228d45f84207e00c591932bd74079cf981e/table_of_data.png)


`@script`
Here we have a table of data and it represents a warehouse in the back of this shop. It’s all the same item, but they have a unique SKU based on the date on which they were manufactured. You just found out that everything manufactured in the last week needs to be sent back. We’re going to do some formatting to point out which items those are.


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
The next thing that you probably noticed by now is that I’m in a country that is showing the month first, and then the day, and then the year. You might not be. Just make sure yours is right for the way you want to work on it.


---
## Localization settings

```yaml
type: "FullImageSlide"
key: "77cb9baa5f"
center_content: true
```

`@part1`
![settings](http://assets.datacamp.com/production/repositories/3835/datasets/0983906b57a3f066ff0c06a195e6509fd8aad68f/settings_zoomed_out.png)


`@script`
Go to file, spreadsheet settings, make sure the locale is correct.


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
Mine is the United States. If that’s not correct, change it here if you need to. Then, you can work with the dates in a way that makes sense to you.


---
## Highlight Your Dates

```yaml
type: "FullSlide"
key: "ddb2305838"
center_content: true
```

`@part1`
![Highlight the Dates](http://assets.datacamp.com/production/repositories/3835/datasets/7f362b96b365ee0d6510aea95ab4e35ba79ed015/highlight_dates.png)


`@script`
The first thing that I would do I highlight the dates that you want to work on. I would just highlight the column with the dates. I wouldn’t highlight any of the other columns because Google Sheets might think that those other values are dates too. Then, you can start your conditional formatting.


---
## Conditional Formatting Menu Option

```yaml
type: "FullImageSlide"
key: "277558f41a"
```

`@part1`
![Menu](http://assets.datacamp.com/production/repositories/3835/datasets/77136595be165d0148745d235a61178aefaad191/menu.png)


`@script`
Go up to Format on the menu and then Conditional Formatting. You’ll get this little dashboard that you see on the right.


---
## Within the Last Week

```yaml
type: "FullImageSlide"
key: "97ac571745"
center_content: true
```

`@part1`
![Within the Last Week](http://assets.datacamp.com/production/repositories/3835/datasets/b9cd0709c0e00e9e4c679eb0607193afa3716cd6/date_is.png)


`@script`
There’s three options here and they're all pertain to today's date. All three of these are going to operate differently tomorrow and they will have operated differently yesterday as well. 

I am going to use Date is. What I am actually looking for is all of the items that were made in the last week.


---
## Date is Before

```yaml
type: "FullImageSlide"
key: "22f63169d5"
center_content: true
```

`@part1`
![Date is Before](http://assets.datacamp.com/production/repositories/3835/datasets/1466cdac73cc2be7cf5967b8f8e5e211e5128a19/date_is_before.png)


`@script`
At first, you might think that you want to look at Date is before. But, be careful. If you do Date is before, what will happen is that is that it is going to start one week in the past and go backwards. If you were to choose that, it would highlight everything more than 7 days old. That’s not what you want. Use the Date is choice on the menu.


---
## In the Past Week

```yaml
type: "FullImageSlide"
key: "ca2b3705c4"
center_content: true
```

`@part1`
![In the Past Week](http://assets.datacamp.com/production/repositories/3835/datasets/b2ed09470a672912a44fbd447c9108f99aa1aac1/in_the_past_weeek_menu.png)


`@script`
In the next box, you want to use the Past week in order to get the last seven days.


---
## Result Showing in the Past Week

```yaml
type: "FullImageSlide"
key: "0ad552a2b2"
center_content: true
```

`@part1`
![In the Past Week](http://assets.datacamp.com/production/repositories/3835/datasets/20c1e777f52fe4e97daf5fab2076b4588ec54e1c/in_the_past_weeek.png)


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

