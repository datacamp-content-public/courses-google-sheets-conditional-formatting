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
!(http://assets.datacamp.com/production/repositories/3835/datasets/dc08a0e8ba4bdb5e6e01ab60323783138b2f0ba1/table_of_data.png)


`@script`
We have a table of data here and it represents a warehouse in the back of this shop. It’s all the same item, but they have a specific SKU based on the date on which they were manufactured. You just found out that everything produced in the last week needs to be sent back. We’re going to do some formatting to point out which items those are that were made in the last week but, before we do that, there’s a couple of setup items that we need to be aware of.


---
## "Today's" Date

```yaml
type: "FullCodeSlide"
key: "4647993e0e"
```

`@part1`
`=TODAY`
10/20/2018


`@script`
The first thing is today’s date. Some of these actions that we are going to do are dynamic because of what the date is. It is helpful to know that today is October 20, 2018.


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
The next thing that you probably noticed by now is that I’m in a country that is showing the month first, and then the day, and then the year. You might not be. Just make sure yours is right for the way you want to work on it. Go to file, spreadsheet settings and make sure the locale is correct. Mine is the United States. If that’s not correct, change it there. Then, you can work with the dates in a way that makes sense to you.


---
## Highlight Your Dates

```yaml
type: "FullSlide"
key: "ddb2305838"
```

`@part1`



`@script`
The first thing that I would do I highlight the dates that you want to work on. I would just highlight the dates. I wouldn’t highlight any of the other columns because Google Sheets might think that these are dates too. Then, start you conditional formatting.


---
## Within the Last Week

```yaml
type: "FullCodeSlide"
key: "fb2ccf026d"
```

`@part1`
No - Date is before
Yes - Date is


`@script`



---
## Result showing last week's items

```yaml
type: "FullImageSlide"
key: "40bd134c38"
```

`@part1`



`@script`



---
## Two More Days

```yaml
type: "FullSlide"
key: "c1c283003e"
```

`@part1`
Is between


`@script`



---
## Result Showing Two More Days

```yaml
type: "FullImageSlide"
key: "951cc2d8d6"
```

`@part1`



`@script`



---
## Let's Practice!

```yaml
type: "FinalSlide"
key: "d180471a53"
```

`@script`


