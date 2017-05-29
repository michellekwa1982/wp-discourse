# WP Discourse
[![OpenCollective](https://opencollective.com/wp-discourse/backers/badge.svg)](#backers) 
[![OpenCollective](https://opencollective.com/wp-discourse/sponsors/badge.svg)](#sponsors)

**Note:** the wp-discourse plugin requires >= PHP-5.4.0.

The WP Discourse plugin acts as an interface between your WordPress site and your
[Discourse](http://www.discourse.org/) community.

###Use Discourse for comments:

- Automatically creates a forum topic for discussion when a new blog post is published.
- Associates WP author accounts with their respective Discourse accounts. Does not require SSO.
- Replies from the forum discussion can be embedded in the WP blog post. Select which replies to display
based on post score and commenter "trust level" -- see docs.

#### See it live

- [blog.discourse.org](http://blog.discourse.org/)
- [boingboing.net](http://boingboing.net/)
- [howtogeek.com](http://www.howtogeek.com/)

### Single Sign On

The plugin also comes with optional SSO functionality which lets you use your WordPress site as the
Single Sign On provider for your Discourse forum.

This will override Discourse's native (and powerful) login flow and is only recommended for use cases
that strictly require such a setup, e.g. a site that is already using WordPress for large scale user management.

### Contact

- The plugin is being developed by [scossar](https://github.com/scossar) on behalf of the Discourse team.

- Bug reports and other developer inquiries should be directed at our GitHub Issues:
[https://github.com/discourse/wp-discourse/issues](https://github.com/discourse/wp-discourse/issues)

- Please post support requests to our [dedicated support forum](https://meta.discourse.org/c/support/wordpress)

### Installation

#### From your WordPress dashboard

1. Visit 'Plugins > Add New'
2. Search for 'WP Discourse'
3. Activate WP Discourse from your Plugins page

#### From wordpress.org

1. Download WP Discourse
2. Upload the 'wp-discourse' directory to your '/wp-content/plugins/' directory
3. Activate WP Discourse from your Plugins page

#### With Composer

If you're using Composer to manage WordPress, add WP-Discourse to your project's dependencies. Run:

```sh
composer require discourse/wp-discourse ~1.3.2
```

Or manually add it to your `composer.json`:

```json
{
  "require": {
    "php": ">=5.4.0",
    "discourse/wp-discourse": "~1.3.2"
  }
}
```

For more detailed instructions please see the [setup](https://github.com/discourse/wp-discourse/wiki/Setup) page of the
[wp-discourse wiki](https://github.com/discourse/wp-discourse/wiki)

### Frequently Asked Questions

#### Does this plugin install Discourse for me?

No this plugin acts as an interface between Discourse and WordPress. For it to work you will need to first set up
Discourse forum. You can install Discourse for yourself following either of these guides:

- [Install Discourse in Under 30 Minutes](https://github.com/discourse/discourse/blob/master/docs/INSTALL-cloud.md)
- [How to use the Discourse One-Click Application on DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-use-the-discourse-one-click-application-on-digitalocean)

#### Can I import old WordPress comments as Discourse comments (i.e. "replies")? 

No.

#### Do WordPress and Discourse have to be installed on the same server?

The plugin uses the Discourse API, so your forum and blog can be hosted separately and the integration will still work.
In fact, we strongly recommend hosting the two applications separately, since their hosting requirements are very different.

#### Is it possible to customize the comment templates?

Yes, the html templates used for publishing posts on Discourse and for displaying comments on WordPress can be customized in your theme.
This is done by hooking into the filters that are applied to each template.

For more details on template customization, take a look at this section of our wiki: [Template Customization](https://github.com/discourse/wp-discourse/wiki/Template-Customization)

#### Contributing

1. Fork this repo
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new pull request

#### Backers 

 [[Become a backer](https://opencollective.com/wp-discourse#backer)]

<a href="https://opencollective.com/wp-discourse/backer/0/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/0/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/backer/1/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/1/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/backer/2/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/2/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/backer/3/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/3/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/backer/4/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/4/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/backer/5/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/5/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/backer/6/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/6/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/backer/7/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/7/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/backer/8/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/8/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/backer/9/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/9/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/backer/10/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/10/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/backer/11/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/11/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/backer/12/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/12/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/backer/13/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/13/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/backer/14/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/14/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/backer/15/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/15/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/backer/16/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/16/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/backer/17/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/17/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/backer/18/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/18/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/backer/19/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/19/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/backer/20/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/20/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/backer/21/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/21/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/backer/22/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/22/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/backer/23/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/23/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/backer/24/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/24/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/backer/25/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/25/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/backer/26/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/26/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/backer/27/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/27/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/backer/28/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/28/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/backer/29/website" target="_blank"><img src="https://opencollective.com/wp-discourse/backer/29/avatar.svg"></a>

#### Sponsors 

 [[Become a sponsor](https://opencollective.com/wp-discourse#sponsor)]

<a href="https://opencollective.com/wp-discourse/sponsor/0/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/sponsor/1/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/1/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/sponsor/2/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/2/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/sponsor/3/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/3/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/sponsor/4/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/4/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/sponsor/5/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/5/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/sponsor/6/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/6/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/sponsor/7/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/7/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/sponsor/8/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/8/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/sponsor/9/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/9/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/sponsor/10/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/10/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/sponsor/11/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/11/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/sponsor/12/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/12/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/sponsor/13/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/13/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/sponsor/14/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/14/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/sponsor/15/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/15/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/sponsor/16/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/16/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/sponsor/17/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/17/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/sponsor/18/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/18/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/sponsor/19/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/19/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/sponsor/20/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/20/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/sponsor/21/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/21/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/sponsor/22/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/22/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/sponsor/23/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/23/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/sponsor/24/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/24/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/sponsor/25/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/25/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/sponsor/26/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/26/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/sponsor/27/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/27/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/sponsor/28/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/28/avatar.svg"></a>
<a href="https://opencollective.com/wp-discourse/sponsor/29/website" target="_blank"><img src="https://opencollective.com/wp-discourse/sponsor/29/avatar.svg"></a>

