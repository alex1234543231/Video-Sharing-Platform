# Video Sharing Platform

## Troubleshooting

! To fix bugs, updated some package codes like the following:

| File | Fix |
| --------------------------- | ----------------------------------------------------------- |
| flask/sessions.py           | from collections.abc import MutableMapping                  |
| werkzueg/datastructures.py  | from collections.abc import Container, Iterable, MutableSet |
| jinja2/tests.py             | from collections.abc import Mapping                         |


This project is inspired by the short comings of Social Media Platforms. It is essentially an Anti Social Network that doesn't conform to normal standards of Social Media. What makes this platform so different is that if a video gets a voting rating of -5 it is then deleted from the database unless a post has been reposted or saved to a users profile and in that case it only exists on the users profile and is not accessible to other users. If a person has 3 videos taken down then their profile and all other associated data is deleted. I think that having the platform set up in this way gives the responsibility to the users of the site to ensure videos are taken down because it's all about how they vote and also the fact that the platform doesn't let users set upload their own videos or pictures. Users can only use external links to point to pictures and videos. This also helps keep the database size small.

(NB) Yet to incorporate the automatic deleting of profiles and videos. (Last Major Code Change)

## UX

## Design

## Features

## Technologies Used

## Testing

### Manual Testing

### Unit Testing

## Deployment

### Heroku Deployment Steps

## Content

## Media

## Acknowledgements

