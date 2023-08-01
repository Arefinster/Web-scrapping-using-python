# module_11_challenge

This is an exercise on web-scraping using Python's libraries Splinter, BeautifulSoup, Pandas and Matplotlib. There are two
tasks in this exercise.

In part 1, we import the splinter and BeautifulSoup libraries. We invoke Browser to open the chrome browser. We visit a
website and parse the html content in the page. In the html body,  We find all the divs containing text elements and print
that on the console for investigation. We then loop through the soup object, obtain the class "content_title" as title and
the class "article_teaser_body" as preview. We save these two items against corresponding keys in a disctionary. At each
iteration, this dictionary is saved as a list item. Finally we display the list content in console.

In part 2, we are scraping info from a table about Mars atmosphere that is recorded in a given website. We parse the website
using B.Soup to find the class 'table' and class 'data-row'. That gives us access to all the rows in the table. We then find 
the tag 'td' to obtain the value of each column. The column headers are acquired using the tag 'th' and saved in a list. Then 
data rows in list and the headers are combined to create the dataframe df. The queries are straight-forward and same as many
other past exercises.

### Answer to the questions in the Requirement section are addressed as bold in this font.




NOTE: In this exercise, I worked by myself. Did not take BCS assistant.

