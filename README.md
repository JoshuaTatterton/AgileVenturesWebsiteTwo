# AgileVentures WebSiteTwo

This was our final Ronin project which we had two weeks to implement while regularly meeting with our client [AgileVentures](http://www.agileventures.org). Our client wanted a new sister site for the current one which consisted of a showcase of completed IT developing projects AgileVentures had helped charities with. They also wanted a way for charities to advertise their IT needs.

See our final project on Heroku [here](https://fathomless-plateau-2837.herokuapp.com)

#### Skills Used

- We pair programmed remotely amongst the group, used waffle to manage our different user stories and tasks to be completed and also used git for version control and branching.
- I spent time working on the back-end of the project and used the migrations in Ruby on Rails to develop the database structure.
- Later in the project once the back-end was completed I helped build the functionality in parts of the website in HTML and later on assisted with the fine tuning of the CSS.

#### Skills Gained/ Improved

- Using waffle was a new experience of managing our time over a longer project length than what I was used to.
- I learnt how to meet with a client and how to interpret their ideas into what is feasible and further what is essential and what is optional.
- The CSS I helped with was more complex than what I was used to so it was good practice.
- I leant how to to use Amazon Web Services to host images on the internet.

#### Technologies Used

- Production: Ruby on Rails, Heroku, Devise, PSQL, HTML, CSS, PaperClip, Amazon Web Services
- Testing: Rspec, Capybara, Database Cleaner

#### How To Use

- To implement this code first clone the repo and run bundle to install all relevant gems.
- You can launch the website locally using rails server. 
- Images uploaded are stored locally while in development but when in production you will need to set up an Amazon Web Service bucket. You will then need to export the following environment variables, ENV['S3_BUCKET_NAME'], ENV['AWS_ACCESS_KEY_ID'] and ENV['AWS_SECRET_ACCESS_KEY'].

The Ronin team consisted of me, [Winnie](https://github.com/winnieau), [Parminder](https://github.com/ajitsy), [Richard](https://github.com/RichardCharman), [Balint](https://github.com/squarebe) and [Sam Joseph/ Tansaku](https://github.com/tansaku) was our client representative.