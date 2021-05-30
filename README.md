## Learn It by Teaching It

#### May 29th, 2021

##### Django

`python manage.py testserver path/to/fixture/sample-data.json --noinput` - starts a test server and loads a fixture for testing

`python manage.py dumpdata <app>.<model> --indent 2 > <model>.json` - dumps data from the Django database in JSON format e.g.
`python manage.py dumpdate auth.users --indent 2 > users.json`

##### Cypress

`cy.get(@csrftoken).then((token) => {...` - gets the value of the field named with the '@'.

`cy.fixture('name-of-fixture-file.json').as('mockedUsers')` injects `mockedUsers` into `this` inside your tests

e.g. `cy.get('email').type(this.mockedUsers[0].email)`


##### Learning Techniques

Have a clarity with *how* to proceed is essential for keeping motivation with your goals.
If you don't know the next steps of what to do then you will eventually lose momentum and give up.
I've personally experienced this many many times where I have a lofty goal e.g. learn a new language, learning a new
technology, learn to draw, etc, and end up leaving it by the wayside as I didn't have a either a clear goal nor a way
to get there, only a general feeling that I would like to "become good" at something.

These three components make up self-regulation, which can be defined as the psychological process that detects inconsistency
between your goals and your behaviours.

- *Self-monitoring* helps you determine how well you are doing
- *Self-evaluation* lets you judge the difference between your actual performance against what you've planned
- *Self-reaction* is how you feel about your performance compared to your goals. If you don't feel good about your goals
  you will realign your motivation to avoid this in the future.

It should be noted that having clarity on what you're doing is only necessary for the next step or two, you don't
need to figure everything out at once.

There are other things that you will need to make progress on your goal

1. A check-point
2. A deadline
3. The right tools and systems
4. A support structure

Something to further check out is "Context-based learning". It can be summarized as follows:

1. Learn a concept (you can get even more out of this by trying to teach the concept, see Feynman Technique)
2. Practice the concept in as close to a real world scenario as possible (role play could work well)
3. Get coaching and feedback
4. Practice
5. Get coaching and feedback


To learn to the point of automaticity i.e. "understanding without effort" takes these four steps:

1. Repeated learning of a small set of information. The important point is to go beyond the initial point of mastery.
2. Make the training progressively more difficult. Make the task harder and harder until it is too hard, then dial it back a bit.
   One thing I've read long ago is that the optimum ration of right to wrong answer is 80/20 (big surprise)
3. Add time constraints. This is to give up trying to be perfect and to increase the difficulty by adding another component to
   think about while doing the task.
4. Do the skill while trying to do something else. Apparently this is to solidify applying what you've learned in different
   contexts, but I'm a bit skeptical this will work since you want to avoid multi-tasking as much as possible.

Somewhere in this article it gets to point 3 "Set Specific Goals with a Hard Time Line". Once you have learned something/trained it
you apply it to the real world. You can do this by setting a very ambitious goal that requires you to use the knowledge you've gained.


