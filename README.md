# Check Your Undersanding

1. Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.
   
This means the tests will run automatically every time I add new code, which helps catch bugs early. It also stops broken code from getting added to the main project, which is really helpful when working with a team. Running tests like this keeps everything working and avoids problems later on.

1. Would you use an end to end test to check if a function is returning the correct output? (yes/no)

No, I wouldn’t use an end-to-end test, but I would rather use a unit test. End-to-end tests are for checking how the whole website or app works from the user's point of view. 

1. What is the difference between navigation and snapshot mode?
   
Navigation mode checks how fast and smooth the website loads from the very beginning. It looks at things like load speed and how much stuff the browser has to do when the page opens which is for testing performance after the page loads. Whereas, snapshot mode just takes a screenshot of the page in its current state. It’s useful for checking things like accessibility and SEO, but it doesn’t show how fast the site loads or how it behaves when users interact with it.

1. Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

* A lot of the product images are big and slow things down. So compressing them and using faster formats could save hundreds of kilobytes and help the site load faster.

* Lighthouse says there’s a lot of unused JavaScript and CSS (2.5MB of JS). Removing that unused code would reduce the load time and make the site run more smoothly.

* The site is missing some key tags like the `<meta name="viewport">`. On the report it says "
Document does not have a meta description". Adding this helps with mobile responsiveness and improves SEO so the site performs better on search engines.




