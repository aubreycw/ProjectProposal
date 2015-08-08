# Hamster Tracker

[Heroku link][heroku]

<!-- TODO -->

[heroku]: http://www.google.com

## Minimum Viable Product
Hamster Tracker is a general tracking app, which makes understanding the relationships between your tracked data easy. Users can:

<!-- This is a Markdown checklist. Use it to keep track of your progress! -->

- [ ] Create accounts
- [ ] Create sessions (log in)
- [ ] Create tracking subjects (hamster health)
- [ ] Create tracking subject attributes (weight, shinyness, walnuts eaten)
- [ ] Choose range and type of attributes (weight is a float, shinyness is an int from 0 to 5)
- [ ] Enter data points
- [ ] View a graph of each tracking subject (against time)
- [ ] Change which attributes are displayed on the graph
- [ ] View a table of correlations for each tracking subject
- [ ] Choose which other users can view and add data to thier tracking subjects

## Design Docs
* [View Wireframes][views]
* [DB schema][schema]

[views]: ./docs/views.md
[schema]: ./docs/schema.md

## Implementation Timeline

### Phase 1: User Authentication, Tracking Subject Creation (~1 day)
I will implement user authentication (using the Rails pattern used at App Academy). By the end of this phase users will be able to sign in, sign up, and create new tracking subjects from a form on the webpage. I will have the app pushed to Heroku.

[Details][phase-one]


### Bonus Features (TBD)
- [ ] Linear lines of best fit on graphs
- [ ] Non linear options for lines of best fit
- [ ] Automatic choosing of best function for line of best fit
- [ ] View attributes graphed against other attributes (instead of time)

[phase-one]: ./docs/phases/phase1.md


