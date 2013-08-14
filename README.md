# gobalt

This is currently a prototype SPIKE to evaluate implementing a cgi-bin endpoint in #golang.

Short version: Totally plausible and would modify this code to do it.

Slightly longer version:

#golang has built in packages for CGI and FastCGI. The code more or less just plugs these together
with a wrapper that calls the Unix utility "su".

Not done:

select user to switch into (the box id) based on URL.
documentation
select the right cwd
deployment

See cards.
