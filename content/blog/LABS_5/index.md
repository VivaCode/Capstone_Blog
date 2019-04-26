day 1:
https://trello.com/c/okYatJQh/169-specify-nyc-under-logo
https://github.com/labs11-homeless-services/web/pull/157
https://trello.com/c/aL5dcaka/172-landing-buttons-color-should-be-white
https://github.com/labs11-homeless-services/web/pull/156

day 2: 
https://trello.com/c/o2Luertq/195-main-cat-button-100x100
https://trello.com/c/OPYKJ7eo/198-back-to-cat-should-be-straight
https://trello.com/c/2JTIw2ny/202-breadcrumbs-between-25-px
https://github.com/labs11-homeless-services/web/pull/168
https://trello.com/c/EunNR9sg/197-remove-shading-on-breadcrumbs
https://github.com/labs11-homeless-services/web/pull/170

day 3:
https://trello.com/c/00hQso53/230-create-media-query-for-breadcrumbs-that-styles-to-upright-tablet
https://github.com/labs11-homeless-services/web/pull/183
https://github.com/labs11-homeless-services/web/pull/187
https://github.com/labs11-homeless-services/web/pull/188
https://github.com/labs11-homeless-services/web/pull/192
https://github.com/labs11-homeless-services/web/pull/194
https://github.com/labs11-homeless-services/web/pull/198

day 4: 
https://trello.com/c/HqLgnuFM/239-tabnav-responsiveness-for-tablet-and-mobile-vertical-and-landscape
https://github.com/labs11-homeless-services/web/pull/210

Part 1 - Individual Accomplishments this Sprint
This sprint was about fine tuning the tab navigator. This one peice of the puzzle has become my greatest accomplishment and my achilles heel. Once it was mostly where it should be and doing what it should do, I needed to focus on responsiveness. It required acknowledging each view a person might use with their device. Matt pointed out that one of his tablet views was skewed. It turned out he was looking at it vertically, not horizontally as the spec was laid out. Armed with this information I created new breakpoints to address vertical and horizontal on tablet, large phones and small phones. 

I also contributed to the constructing of the readme, added a tagline plus styling and updated the icon for the language buttons.

Detailed Analysis

Pull request 210 is the one I worked the hardest on this week. Styling is definitely a weak spot for me so I was nervous going in. We had a meeting with OLU this week and got final feedback that I needed to address ( spacing, font sizes, colors ). During one of many group tests were we pulled the app up on various devices we found that when a table was verticle the alignment of the breadcrumbs were very off. This inspired me to do more of that with other devices. In all I ended up creating 6 individual breakpoints to address various screens and viewing methods. This required me to make use of ids in a couple places where the design needed to move, but not be completely done away with. At times it felt like creating speghetti code with all the different media views, two separate places the styling had to be mirrored occassionaly and multiple classes that could only be placed on specific buttons.

Because of the way the array outputs it was impossible to exclude the main category button when styling the tabs as a unit. I wanted originally to place a container around the tabs without the main category button so that styling for different views, it would be simpler to to adjust the veiws but bc it was an array that included the main cat, it was not possible to get between.

Part 2 - Weekly Reflection

While I love what the final product is, there is so much that still feels "imperfect" The layouts were a challenge to get right on every device. We never got the active tab working so that the color stayed flipped for the tabs. I would have loved to have seen all the landing pages do away with the search. I wish I had been able to add more results to the search algorithym. The data was never quite right. I blame only myself for all these things. I was definitely the weakest link of the team. 

It was an amazing experience. I've learned so much about working on a team, interpersonal communication and where I need to dig in to be a better developer on a techincal level. I am really grateful for that. It was an experience that could not have been more under sold.