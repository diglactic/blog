---
layout: post
title: "Getting Ahead of Downtime"
---

The latest changes are pushed. Your servers are up to date. Project complete, case closed.

And then it happens. A frantic call, email, or text telling you the site is down. You respond in the only way you can:
panic. *Is my hosting provider down? Did the domain name expire? Did I break something in the code base? Worse, was
there a malicious attack?* Once that first email comes in, it's a scramble for dear life. Every minute counts to get a
site back up and running and save face in front of your client and their customers.

At Diglactic, we approach this problem by beating the unexpected in two key ways. First, we make sure to install bug
trackers on every project we build. If an end user or the system internally encounters an error (like a CRON job), we'll
get an alert and can react accordingly. Many times, errors that take down a site (or affect a lot of users) are first
seen by one or two users earlier on. Getting ahead of those issues can prevent unnecessary headaches later on.

Second, we configure a heartbeat ping to check in every few minutes on our website to see if it's loading. This can also
pick up on simple oversights like misconfiguring an SSL certificate or forgetting to renew a domain name. Internally, we
have a status page set up with each of the sites we maintain to keep track of downtime, and we'll get an email delivered
to our inboxes within minutes of a site going down.

![Internal status dashboard screenshot](/assets/images/posts/2020-11-18-getting-ahead-of-downtime--status-dashboard.jpg)

*Our internal uptime dashboard*

While this isn't a bulletproof solution (a logic issue, for instance, could very well pass through undetected), it'll
catch the majority of site uptime issues.

You don't have to (nor should you) be an incredibly large agency to ensure your client's sites are running smoothly. It
doesn't have to be costly, either. (If you're in e-commerce, any price will likely be quickly justified.) Here are some
of our favorite services (most of them even have free tiers!):

- [UptimeRobot](https://uptimerobot.com/)
- [Oh Dear](https://ohdear.app/)
- [Bugsnag](https://www.bugsnag.com/)
- [Sentry](https://sentry.io/)

The next time something goes down (and it will), make sure you're the one sending the email and not receiving it. It'll
make a world of difference.
