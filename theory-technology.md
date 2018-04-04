---
layout: page
title: Theory & Technology
---

# The Theory: An Ergonomic and Minimalist Approach to Data.

Data ergonomimcs. If it sounds made up, it's because it is. A little.

Ergonomics is concerned with designing and arranging people and tools to create a more effective process. Applied to data, this means pragmatically defining your data-to-be and designing the data-system to integrate easily into staff workflows. Staff’s intrinsic motivation to communicate their important work meets resistance when data-systems are overly-bothersome, and collected data feels unused. By improving the way people enter and access data, non-profits can build data buy-in naturally using staff’s intrinsic motivation to story-tell.

# The Technology: Cutting Edge Software adapted for Social Change

Theory is nice, but it's nothing without tools.

### Collection

Central to data ergonomics are data tools to meet people where they are at. PowerApps allows the creation of database interaction apps through a graphical user-interface.

"Oooooh, a web-based GUI tool to create enterprise apps that look feel sloppy compared with the Silicon Valley native apps", you might be saying.

First, no one likes a tech snob. They may not be as snappy as something from the App Store, but don't underestimate these apps, they skip the diploma-long learning curve and can be made in days instead of weeks. If you're shy a couple $100k for a native-developed app, these will do.

Second, these apps outpace native apps in a crucial way they can be accessed from any platform. That's right, make one app and access it from your Android phone, your Windows tablet, or your Mac's web-browser. This level of accessibility is unheard of in mobile technology. The closest equivalent would be a custom web-responsive website (and a couple $100k).

### Architecture

Because we use PowerApps to collect the data, our options for collection are limited to Microsoft tech. But because Microsoft never stops coding to take and break and see if there's any overlap in the tech their making, you still have a few operations

#### The Common Data Service

For smaller non-profits looking for a lightweight implementation, Common Data Service is the way to go. It let's you define entities (like "Dinosuar", or "Natural Disasters") and then give those entities any data field you'd like (such as "Scaryness, (integer, 0-10)" or "reptiles exterminated (integer, 0-1000000)"). Though the graphical user interface to play with this data is lacking, PowerApps can step in to do the work.

#### Dynamics 365

This starts to stray from lightweight as setting up Dynamics requires more expertise and time to set up. Once it is set up though, Dynamics offers a powerful user interface to edit and search your organization's data.

#### Excel

Some people absolutely love excel, and we're not here to convince them otherwise. PowerApps can read from, and enter data into Excel sheets, though managing your excel sheets may take a bit neuroticism. It's worth mentioning that the solutions above can both export to excel.

### Visualization

This is the best part. All the hard work entering that data leads up to the point when the graphs really come to life.

#### PowerBI

This gets first mention because it's easy. Connect your database above to PowerBI in a couple clicks and then have way too much fun making interactive graphs.

#### D3

When you want a public data visualization super-customized and mobile-responsive, there's no better solution than the open-source javascript library D3 (Data Driven Documents).

##### Others (Tableau, Excel, etc.)

If you have excel sheets, there's a ton of software that will help you visualize it. If you're keen to use something else, power to ya.
