# needhamcircle.org

This organization contains the source code for the Needham Circle website. There are three components:

* [`ingest`](https://github.com/needhamcircle/ingest) - a sync script that runs once a day and ingests events from town calendars into a backing Google Calendar
* [`functions`](https://github.com/needhamcircle/functions) - serverless functions that power the Needham Circle website for fetching events, submitting events, and handling contact forms
* [`needhamcircle.org`](https://github.com/needhamcircle/needhamcircle.org) - the main website repository, a static site built with Jekyll
