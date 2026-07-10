
# Seattle Fire Department Incident Card

Work in progress to create a Winlink form to automate the process described in this page from the Seattle ACS Action Plan for a recent SFD Windshield

Exercise:

![Incident Card example from a past SFD Windshield Exercise](images/SFD_card_example.jpg)

## Another example incident card

This image has better resolution, note the faint writing:

![Appendix 3 - Incident Card (example)](images/IMG_1217.jpeg)


A first pass at a Winlink form was presented at the May 2026 ACS meeting,
resulting in a lot of great feedback, listed in
[Issue #4](https://github.com/rjleveque/SeattleACS_wl-forms/issues/4).



## Draft of 2026-07-09

A greatly improved version was generated with a lot of
help from Claude Code.

### Try out the web browser version

You can type into [this live sample version](https://faculty.washington.edu/rjl/hamradio/SFD_incident_card-form.html).  Note that the Save button should save a file to your local computer (which could later be transferred to Winlink), and
the Load button now works to reload data.

There is also now a "Print Card" button to print out the
data in a form that can be cut out to produce a card with
the same shape and general look as the physical cards.


### Install in Winlink

To try it in Winlink, copy these files into your Winlink Express `Global Folders\Templates` directory:

- SFD_incident_card-form.html
- SFD_incident_card-template.txt
- SFD_incident_card-viewer.html

Then compose a new message, selecting the template under `General Templates`.

This should open a browser window that looks the same as the sample web version above, but if opened from within Winlink the "Submit" button should work to translate the html form information into a Winlink message, which you can then "Post to Outbox".

The Viewer version allows an incoming Winlink message
based on this form to be nicely displayed in a browser.
The "Print Card" button also appears in this view.

## More details

To appear.

## Notes

- This is a draft. I'm soliciting input.

- There's no Viewer form yet for converting an incoming Winlink message to a nice html version.

- Many thanks to Jon K7RMZ for running a workshop and providing several examples at his [Winlink Forms Training Github Repo](https://github.com/nojronatron/wl-forms-training)

Some ideas also adapted from:

- K7RMZ's [Bigfoot bib tracker form](https://github.com/nojronatron/Bigfoot-Bib-Report-WL-Form)
- Info on the Winlink pages [create_template.pdf](https://winlink.org/sites/default/files/RMSE_FORMS/create_templates.pdf)
