<<<<<<< HEAD
![MaptimeDC logo](https://cloud.githubusercontent.com/assets/1833870/3643697/ab9000a0-10d7-11e4-96a6-72bd79a835e7.jpeg)

# #Maptime DC!

[![Join the chat at https://gitter.im/maptime/dc](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/maptime/dc?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Welcome to the repo for the DC chapter of #Maptime!

*What's Maptime? Check out [this description](http://www.maptime.io/about/)*

## Meeting Info
- We meet the third Tuesday of every month, usually at the [Digital Commons Dream Lab at MLK library](http://dclibrary.org/digitalcommons)
- Please consider joining the [Meetup page](http://www.meetup.com/Maptime-DC/) to keep informed on upcoming events

## Resources
- Looking for information or material from a past event? Start **[here](/Events.md)**

## Contributing

The primary way you can contribute to this repo is via the Issues section with:

1. Suggestions for future Maptime events, including offers for you to present
2. Comments or questions about a specific event that you attended
3. General comments about Maptime DC structure, venues, etc
4. An introduction.  Be social!

## Contact Us
Check us out on twitter: [@MaptimeDC](https://twitter.com/MaptimeDC) or on [Meetup](http://www.meetup.com/Maptime-DC/)
=======
## Maptime Starter site

Starter is a simple Jekyll theme for MapTime meetups. Hosting your own meetup? Starter is desgined to be easily forked and tweaked to suit your own needs.

## Installation

1. [Fork this repo](https://github.com/maptime/starter/fork/).
2. Edit the [`_config.yml`](https://github.com/maptime/starter/blob/gh-pages/_config.yml) file. Here's a quick rundown of the configuration options.

| Name | Required | Value | Description |
| --- | --- | --- | --- |
| baseurl | Yes | post | This value should always be the same. |
| permalink | No | how urls are generated | You can learn more about how they are generated [here](http://jekyllrb.com/docs/permalinks/). |
| markdown | No | Determines which markdown engine is used | Generally, you don't need to touch this field for your own needs. |
| paginate | Yes | Number of posts on the front page | Starter supports pagintaion. Control the number of posts on a given page by changing this value |
| repo | Yes | Name of the repo on GitHub | As an example, the name of the starter repo is `starter` |
| github_org | Yes | Name of the organization or username on GitHub | Most of the time this will be 'maptime' |
| maptime: chapter | Yes | Name of your MapTime meetup | |
| maptime: twitter | No | Your MapTime Twitter username | |
| maptime: disqus | No | Disqus account name | Starter optionally supports comments on posts with [Disqus](disqus.com). Create a new Disqus account for a site and fill this field with the account name. |

### Content types

There are two kinds of content in Starter: post and event. You author these types of content in the `_posts` directory. Each content type has unique configuration options that you should declare at the top of the document. This is called [Frontmatter](http://jekyllrb.com/docs/frontmatter/).

#### Event
Events are for actual planned meetups with RSVP information. Note that the filename of the post should match the date of the meetup date.

##### Fronmatter options

| Name | Required | Value | Description |
| --- | --- | --- | --- |
| layout | Yes | event | This value should always be the same. |
| category | Yes | event | This value should always be the same. |
| title | Yes | The title of your event | |
| rsvp | Yes | URL to rsvp | This should be a link to  an [Eventbrite](eventbrite.com) date or other service. |

#### Posts

Posts are like blog posts. These are great for meetup follow ups or posts that don't have a meetup event tied to it.

##### Fronmatter options

| Name | Required | Value | Description |
| --- | --- | --- | --- |
| layout | Yes | post | This value should always be the same. |
| title | Yes | The title of your post | |
| author | No | Author's name | |
| image | No | URL path to an image | Images added here will show up as a [Twitter card](https://dev.twitter.com/docs/cards) when a post is shared. |

## Help resources

- [Create an issue](https://github.com/maptime/starter/issues) on the Starter repo and we'll respond to it.
- The site is powered by Jekyll. To make custom tweaks to your own site, you should read it's [documentation](http://jekyllrb.com).
- Starter makes the assumption you will be running the site on GitHub pages. You can learn more about [GitHub Pages here](https://guides.github.com/features/pages/). 

## Examples in the wild

Have you used this starter to create your own meetup site? Let us know and we can add it below!

- [MaptimeTO](https://maptime.github.io/toronto/)

## License

BSD
>>>>>>> origin/gh-pages
