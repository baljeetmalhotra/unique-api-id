# Unique API Identifiers
This is a project to develop a unique identifier for each public API.

# Draft Proposal
Here is the format being proposed as a starting point for each identifier.

- **entity** - The name of the organization behind API (e.g., twitter.com).
- **protocol** - The protocol used as a transport (e.g., https).
- **domain** - The root domain for organization behind API (public).
- **version** - The version of the API being identified (e.g., v1.1).
- **catgory** - A general or specific resource (e.g., finance).

These would represent each part of the id, delimited using a colon.

## Example ids
Here are some example unique identifiers for some of the leading APIs.

- twilio:http1:twilio.com:2010-04-01:sms
- stripe:http1:stripe.com:v1:payments
- spotify:http1:spotify.com:v1:music
- youtube:public:http1:youtube.com:v3:videos
- twitter:http1:twitter.com:v2:social
- reddit:http1:reddit.com:v1:subreddits

## Relevant Example
This is an example of a naming system for IT systems and software.

- (**Common Platform Enumeration (CPE) Dictionary**](https://nvd.nist.gov/products/cpe)
- (**Common Platform Enumeration (CPE) Documentation**](https://nvlpubs.nist.gov/nistpubs/Legacy/IR/nistir7695.pdf)

This provides a model that we can use to drive the formalization of this.

## Contribute / Support
We are using Github issues to drive the conversation around this specification, and are just getting started so make sure you share your feedback.

## Project Supporters
This project is being driven by a handful of different companies working together.

- [Postman](https://postman.com)
- [TeejLabs](https://apidiscovery.teejlab.com/)
- [API Evangelist](https://apievangelist.com)

If you'd like to get involved feel free to contribute and we'll add your name to the list.
