# NLP-text-analysis

## Backgroud of this project
Miro is an online whiteboard collaborative platform with 12M+ million users all over the world
from companies like Google, Netflix, Spotify, eBay, Twitter, Autodesk, Cisco, Adobe, PwC,
Deloitte, EY, etc.
The audience of the product is super broad. As a product-led and user-centric company, we are
eager to hear the voice of our users to incorporate it into product decisions and to provide a
constant feedback loop between the product, customer-facing teams and users. While our
success is highly dependent on the success of our users and customers, we believe that the
value we deliver to them should be aligned with their needs.

### Business-case
Fundamentally Miro is a wide horizontal product. Our users utilise very basic widgets (shapes,
stickers, connectors, etc.) to achieve their goals. This provides much flexibility but requires extra
manual effort when they need to incorporate some complex visual structure with specific logic.
One of such examples is grid-like (or table-like) structure.

### User/Customer problem
1. Users often create grid-like structures (tables, calendars, kanbans, gantts etc) and the
creation process requires a lot of manual work (create, change place, replace two
objects, replace a line or row etc).
2. Many of the existing Miro templates have a grid structure and have the same problems
as grids created by users (based on shapes and lines). It decreases the retention rate
because of the low speed of work with them.
3. Current Tables widget has a very low retention and don’t solve user problems.

### Solution
Early 2020 we’ve released V1 of Grids in alpha -> beta -> public launch sequence (official
launch was on May 18th).

### Functionality:
● The widget that can be easily set up as the grid of dimensions that users choose (like
2x5, 4x10, etc) with controls that help to add / delete rows and columns in one click.
● To manage a grid we suggest a possibility to change the place of an element with all
content inside (column\row\cell) and also change cells' dimensions.

● In case of templates, Grids are able to make a one-click copy of a row/column to speed
up the process.

● User is able to put all kinds of content inside a cell: text, shape, set of shapes, image, etc

### Value proposition:
Grids in Miro is a very flexible and powerful tool to work visually with structured data or to
organize our content on a board.
Do the most frequent actions in one click: add columns and rows, merge cells, copy columns
and rows and add any object to the table.
Problem - solution (Miro vs Google Spreadsheets)
● Reduce tools switching → One tool for many tasks
● Put important information in one place → Single source of truth
● Use the most important features with simple UI → Short adoption curve, easy to start
Based on usage data (feature activation/adoption/retention) we observe that grids fit target
use-case but overall performance is not as high as it was expected. Based on our initial feature
strategy and usage traction product team considers to elaborate Grids - Version 2.


### Request to analytics
Whereas the product team is working on V2 of Grids, user’s feedback is considered a
valuable source to formulate requirements for the next version of this feature. As a user's
insights analytics manager you need to identify core user’s issues / advancements -> and to
make suggestions of what should we focus on / take into account while developing new Grids

## Dataset
### NPS:
From time to time we ask users about their willingness to recommend Miro (1-10 point scale)
with an option to leave text feedback. How: in-product pop-up window, request initiated by Miro.
![nps](https://user-images.githubusercontent.com/36822899/108904736-2b73b880-761f-11eb-92a2-1dae5be67cfe.JPG)

### Feature feedback:
For several features users are able to reveal their satisfaction (1-5 point scale) and leave text
feedback. How: in-product feature-rating window, feedback initiated by user. Data in the table
provided only for Grids feature.

### Support tickets:
Miro users and site visitors are able to write support requests. How: in-product / on web-site
menu item, request initiated by user / visitor.

### User’s roles:
We collect the data regarding user’s functional roles. When we can’t identify it, we categorise it
as ‘Not detected’.

### User’s segments:
Miro is freemium with two paid segments: self-serve (paid teams) and high-touch (big enterprise
customers). As a user can participate in several teams, he/she can belong to more than one
segment.
