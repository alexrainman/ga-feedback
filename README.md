
# Google Analytics Feedback Plugin for Xamarin

## Receive free and unlimited Feedback simply by using Google Analytics

* Integrated with your Google Analytics data
* Easy to install
* Daily emails + Advanced reports

## How it works

The plugin places a sticky button at the bottom right of the page:

![Feedback button](https://cloud.githubusercontent.com/assets/141241/6185187/ce03b870-b36b-11e4-86a7-a6ef880f95ec.png)

Once clicked, it shows a Feedback form:

![Feedback dialog](https://cloud.githubusercontent.com/assets/141241/6185199/f122f686-b36b-11e4-8858-fb8869824b82.png)

The user can select what type of feedback to send and fill in a text box. Once the user clicks <em>Send</em> a Thank you message shows up and the dialog disappears.

All messages are saved as "Feedback" Events in Google Analytics.

## Feedback Dashboard

The Feedback widget dashboard is a readymade dashboard that displays user's feedback in tables (these are sorted by Number of Sessions per User so more active users show up first). The right column has a few other things like a pie chart and a timeline of all feedback received.

<a href="https://www.google.com/analytics/web/template?uid=DcXKkhvbT1GSHHcOrdkGoA">Click here to get this Dashboard</a>, it's a great starting point and you can customize it further later, keep reading to see how.

![Feedback dashboard](https://cloud.githubusercontent.com/assets/141241/6202018/df394a10-b4ce-11e4-9b75-047aaf44c511.png)

## Get results by email every day

At the top of the Dashboard there's an <em>Email</em> button, click it to get an email with the Dashboard. You can customize Daily, Weekly, Monthly reports and also send it to you and your team:

![Daily email](https://cloud.githubusercontent.com/assets/141241/6202046/85f10072-b4d0-11e4-9bd6-d5f9c7c7f677.png)

### Occasional alert

If you don't want to receive an email every day, Google Analytics has got a feature called <em>Alerts</em> in <em>Intelligence Events</em> which allow you to receive emails when certain things happen. In the example below we receive a daily email when Feedback is submitted:

![Intelligence Events](https://cloud.githubusercontent.com/assets/141241/6192851/649201c6-b3b6-11e4-9b0a-b15783c18b01.png)

You can choose to get an email only when more than 10 people submitted feedback, or filter only "Problems", or just get feedback from returning visitors, or from people that are in the US, or feedbacks that include the word "error", or feedback from users using Firefox...

### Customization and detail

Feedback submissions are saved as Events in Google Analytics (<em>Reporting</em> > <em>Behaviour</em> > <em>Events</em>).

- **Events Category**: <code>Feedback</code>
- **Events Action**: <code>Problem</code>, <code>Suggestion</code>, <code>Compliment</code> or <code>Other</code>
- **Events Label**: User's feedback
- **Events Value**: <code>1</code>

#### Event Actions

![Google Analytics Events Action](https://cloud.githubusercontent.com/assets/141241/6185994/6abf609e-b374-11e4-8e4c-7501001007e5.png)

#### Event Labels

![Google Analytics Events Label](https://cloud.githubusercontent.com/assets/141241/6186019/b39a9fae-b374-11e4-8c98-a1c0ebb52949.png)
