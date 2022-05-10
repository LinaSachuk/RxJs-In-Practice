# RxJs-In-Practice

## This Course in a Nutshell (note: this course includes the Typescript Jumpstart E-Book)

This course is a complete practical guide for the RxJs library (Reactive Extensions for Javascript).

If you are a developer just getting started with the Angular ecosystem, or even if you already have some experience with it, the part that you will find the hardest to wrap your head around is RxJs.

And this is because RxJs and Reactive Programming have a steep learning curve that makes it hard to just jump in into an existing program and learn these concepts by example. With RxJs that approach will simply not work. Instead, we need to start at the beginning and learn some baseline reactive design concepts first.

In this course, we will start by presenting a couple of baseline concepts, and then we will provide you with an extended catalog of RxJs operators that will in practice cover the vast majority of your daily needs.

Also, the goal here is not to cover every single operator, but instead to choose an extended subset that contains the most commonly used operators, and provide practical examples for each.

Another goal of the course is to show how RxJs is meant to be used for building programs using Reactive Design as opposed to an imperative programming style.

## Course Overview

We will start by quickly introducing RxJs: we will cover the notions of Stream and Observable, and we will answer common questions such as: what is RxJs, when to use it and why, what problem does it solve?

We will then write our own Observable from first principles: we will implement our own HTTP observable that will allow us to handle backend HTTP requests while supporting error handling and cancellation.

After this quick introduction, we will dive straight into the practical examples covering a large variety of operators. We will cover the operators by explaining their behavior using the official RxJs marble diagrams, and then we will complement that with a practical example.

We will first start with the Map and Filter operators, and quickly move to more complex operators such as shareReplay, concat, concatMap, and other commonly used observable combination strategies such as: merge and mergeMap, exhaustMap, switch and switchMap. We will provide practical examples for these operators that include backend save operations and search typeaheads.

We will then cover several RxJs error handling strategies, like catch and recover, catch and rethrow or retry.

We will also cover the notion of subject and give examples of several commonly used subjects, such as BehaviorSubject or AsyncSubject. We will then use a subject to implement a very commonly used reactive pattern: we will implement a centralized observable store from first principles.

We will also cover many other commonly used operators, that include but are not restricted to: withLatestFrom, forkJoin, take, first, delay, delayWhen, startWith, etc.

At the end of the course, we will implement our own custom pipeable operator from first principles: we will implement a debugging operator that is going to be very helpful for debugging our RxJS programs.
