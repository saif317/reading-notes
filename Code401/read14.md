# Event Driven Architecture

## What’s the difference between a FIFO and a standard queue?

Standard queues guarantee that a message is delivered at least once and duplicates can be introduced into the queue. FIFO queues ensure a message is delivered exactly once and remains available until a consumer processes and deletes it; duplicates are not introduced into the queue

## How can the server be assured a message was properly received?

messages are grouped into “Message groups” and all messages within a message group are sent and received in strict order. A message group is required to send and receive a message from a FIFO queue

## What classic design pattern is best represented by event driven programming?

Factory Method

## How do you test an event driven system?

unit testing

## FIFO Queue

a queue that operates on a first-in, first-out (FIFO) principle

## Pub/Sub

enables you to create systems of event producers and consumers, called publishers and subscribers. Publishers communicate with subscribers asynchronously by broadcasting events
