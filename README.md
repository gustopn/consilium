# consilium
simple source hosting framework

This project is a try to build some kind of source hosting
framework much like gitlab. The reason why I am starting this
is because I wasted some time with trying to get gitlab running
stable on a test machine with limited RAM.

That was not successful yet and maybe never will be,
because gitlab has serious memory leaks. Even though
they have a mechanism - they call it mechanism - to
work around these issues, they are not being called
after some time, so for a possibly idle server it
means that in worst case it will run out of RAM.

That's plainly inacceptable.

However, during playing around with gitlab,
I was confronted with its working principle
which is pretty darn simple. The most functionality
can be built using standard unix tools.

The main difference would be that my project
would NOT include any ruby code or any non-standard
way of doing things. That's why it can never be as
advanced as some of these cheating projects.
But for a one person project, this would also be
unrealistic anyway, so we keep it simple, stupid.
