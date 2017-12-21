<!--[comment]: # Background change-->
<!--[comment]: # ```diff-->
<!--[comment]: # + this text is highlighted in green-->
<!--[comment]: # - this text is highlighted in red-->
<!--[comment]: # ```-->
<!--[comment]: # Trying to create a pretty md file style-->
<!--- Coment --->
# Markdown guideline
Creating pretty markdown
___
## Summary
- **[Comments](#comments)**<br>
- **[Styling text](#styling-text)**<br>
  - **[Bold](#bold)**<br>
  - **[Italic](#italic)**<br>
  - **[Bold and Italic](#bold-and-italic)**<br>
  - **[Strikethrough](#strikethrough)**<br>
- **[Headings](#headings)**<br>
- **[Lists](#lists)**<br>
  - **[Unordered lists](#unordered-lists)**<br>
  - **[Ordered Lists](#ordered-lists)**<br>
  - **[Nested Lists](#nested-lists)**<br>
  - **[Task Lists](#task-lists)**<br>
- **[Comments](#comments)**<br>
- **[Quotes](#quotes)**<br>

__

## Comments
To comment a markdown file just use

```
<!--  Comment here  -->
<!--- Comment here --->
```
___

## Styling text

### Bold
`** Text **` or `__ Text __`

**Text** or __Text__

### Italic
`* Text * or _ Text _`

*Text* or _Text_

### Bold and Italic
```
Just combine __ or ** (Bold) with _ or * (Italic)

__Is this _important_ yes or no?__

**Is this _important_ yes or _no?_**

__Is this *important* yes or _no?___
```

__Is this _important_ yes or no?__

**Is this _important_ yes or _no?_**

__Is this *important* yes or _no?___

### Strikethrough
```
To strikethrough a text
~~ Wrong Text ~~
```
~~Wrong Text~~

## Headings
Creating Heading sections 
```
Big to small
#      | Header 1
##     | Header 2
###    | Header 3
####   | Header 4
#####  | Header 5
###### | Header 6
```
# Title (1 #)
## Title (2 #)
### Title (3 #)
#### Title (4 #)
##### Title (5 #)
###### Title (6 #)
___

## Lists
### Unordered lists
```
Add - or *
- Apple
- Banana
- Orange
```
- Apple
- Banana
- Orange

### Ordered Lists
```
Just add a number
1. Apple
1. Banana
1. Orange
```
1. Apple
1. Banana
1. Orange

### Nested Lists
```
It is easy
1. First
   - Second
     - Third

Just note the identation and marker character
1. First
___- Marker Character (-) Below the first character of the text
_____- Same as above, note '-' is just below the M
```
1. First
   - Second
     - Third
     
### Task Lists
Create a pretty task list is easy
```
Just use - [ ] (with a space between the brackets)
Done tasks? Just add a 'x' between  brackets ([x])
- [x] Item 1
- [ ] Item 2
- [ ] Item 3
```
- [x] Item 1
- [ ] Item 2
- [ ] Item 3

## Quotes

```
To quote a phrase just use '>'
No quote
> With quote
```
No quote
> With quote



