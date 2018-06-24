
# Google Analytics Feedback plugin for Xamarin

## Receive Feedback simply by using Google Analytics

* Easy to install and use
* Integrated with your Google Analytics data

## How it works

The plugin depends on Google Analytics plugin for Xamarin: https://github.com/alexrainman/Analytics

The next step will be to place an element in your UI, call it a button, a menu item, a banner, etc. Once this element is clicked, execute this line of code:

```
CrossFeedback.Current.Report();
```

A Feedback Activity will be started in Android, a Feedback UIViewController will be pushed in iOS:



The user can select how they feel about the app and type their opinion in a text box. Once the user clicks <em>Submit</em> the form disappears and a Thank you message shows up.

All submissions are saved as "Feedback" Events in Google Analytics.

## Feedback Dashboard

The Feedback widget dashboard is a readymade dashboard that displays user's feedback in tables (these are sorted by Number of Sessions per User so more active users show up first). The right column has a few other things like a pie chart and a timeline of all feedback received.

Feedback submissions are saved as Events in Google Analytics (<em>Reporting</em> > <em>Behaviour</em> > <em>Events</em>).

- **Events Category**: <code>Feedback</code>
- **Events Action**: <code>Angry</code>, <code>Sad</code>, <code>Meh</code>, <code>Happy</code> or <code>Excited</code>
- **Events Label**: User's feedback
- **Events Value**: <code>1</code>

![Feedback dashboard](https://cloud.githubusercontent.com/assets/141241/6202018/df394a10-b4ce-11e4-9b75-047aaf44c511.png)

<a href="https://www.google.com/analytics/web/template?uid=DcXKkhvbT1GSHHcOrdkGoA">Click here to get this Dashboard</a>, it's a great starting point and you can customize it further later.

## Release Notes

Version 1.1

- Adding TintColor RGB parameter to match app design
- Setting comments field max characters to 500 to match Google Analytics event label max bytes
- Disabling paste into comments field
- Applying an EmojiFilter to comments field
- Updating labels
