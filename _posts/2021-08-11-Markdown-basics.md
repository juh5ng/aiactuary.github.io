# This is the basic text marking method.
Markdown can't understand line-break with a simple enter key pressing.

To change the line, "enter" has to be pressed twice at the end of line. 

## 1. There are several highlight markings. 


```

First, *single asterisks* 

Second, _single underscores_

Third, **double asterisks**

Fourth, __double underscores__

Fifth, ~~cancelline~~

```

First, *single asterisks* 

Second, _single underscores_

Third, **double asterisks**

Fourth, __double underscores__

Fifth, ~~cancelline~~


## 2.  There is a lot of kinds of headings

```

# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6
####### This is a H7
######## This is a H8 (Headings don't get smaller after H6)

```

# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6
####### This is a H7
######## This is a H8 (Headings don't get smaller after H6)


## 3. Quatations

```
> This is a blockqute.
> >This is a blockqute.
> >>This is a blockqute.
> >>>This is a blockqute.
> >>>>This is a blockqute.
```

> This is a blockqute.
> >This is a blockqute.
> >>This is a blockqute.
> >>>This is a blockqute.
> >>>>This is a blockqute.


## 4. Sorting lists

```
1.Spring
2.Summer
3.Autumn
4.Winter
```

1.Spring
2.Summer
3.Autumn
4.Winter


## 5. non-Sorting lists

```
* snack
	* ramen
		* candy
			* bicycle
				* umbrella
```

* snack
	* ramen
		* candy
			* bicycle
				* umbrella

```
+ snack
	+ ramen
		+ candy
			+ bicycle
				+ umbrella
```

+ snack
	+ ramen
		+ candy
			+ bicycle
				+ umbrella


```
- snack
	- ramen
		- candy
			- bicycle
				- umbrella
```

- snack
	- ramen
		- candy
			- bicycle
				- umbrella


## 6. Code quotations

```
fuction test() {
	console.log("notice the blank line before this function?");

```
fuction test() {
	console.log("notice the blank line before this function?");

## 7. Programming Language quotations

- ruby


```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

- python


```python
s = "python syntax highlighting"
print s
```

## 8. Horizontal Lines

* * *
***
******
- - -
----------------

## 9. Link 

[linking examples](https://google.com)

<https://google.com>

![](https://images.app.goo.gl/AdfQfLsgeMtXA3nt9)

![](https://images.app.goo.gl/AdfQfLsgeMtXA3nt9){: .align-center}

## 10. Tables

|snacks|prices|counts|
|:---:|:----:|:---:|
|ramen| 1$ | 10|
|bread| 2$ | 20|

|snacks|prices|counts|
|:---|:----|---:|
|ramen| 1$ | 10|
|bread| 2$ | 20|


EoD.

Reference 

1. [취미로 코딩하는 개발자](https://devinlife.com/howto%20github%20pages/markdown-syntax/#210-%ED%91%9C-%EB%A7%8C%EB%93%A4%EA%B8%B0)

2. [마크다운 markdown 작성법](https://gist.github.com/ihoneymon/652be052a0727ad59601#file-how-to-write-by-markdown-md)

