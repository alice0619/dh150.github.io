---
layout: page
title: Japan Culture
permalink: /japanculture/
---

## What's Japan?

## How Are Japanese People Like?

## Greetings
### Basics
- ***Arigatou gozaimasu***.   
(Thank you very much.)
- ***Sumimasen***.   
(Excuse me.)

### Eating
- ***Itadakimasu***.   
(Before meals, "Thanks for the food." Some even liken it to the religious tradition of saying grace before eating.)
- ***Gochisousama deshita***.   
(After meals, “It was a great deal of work (preparing the meal).” Thus, it can be interpreted in Japanese as “Thank you for the meal.")

### Others

## Manners

## Holidays in Japan
Better to avoid those seasons...

# Load
wikihub
  .load({
    token: 'h38d8h48fj49fji39903kfg84hhf84994jff8940',
    owner: 'jake-cool-user',
    repo: 'awesome-wiki',
    branch: 'master',
    path: '_posts/2015-08-01-whatever-happened-happened.md'
  })
  .then(function(text) {
    /* ...do something with text */
  })
  .catch(function(err) {
    /* ...something went wrong */
  });
  
  # Save
  wikihub
  .save({
    token: 'h38d8h48fj49fji39903kfg84hhf84994jff8940',
    owner: 'jake-cool-user',
    repo: 'awesome-wiki',
    branch: 'master',
    path: '_posts/2015-08-01-whatever-happened-happened.md',
    text: 'This is what this post should really be about.'
  })
  .then(function(pull) {
    /* ...changes have been commited */
  })
  .catch(function(err) {
    /* ...something went wrong */
  });
