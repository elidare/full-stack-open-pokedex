Let's say we use Python. We are bulding some web application on Django, having some API, and using Django Templates with HTML.
For linting, we will use Flake8, and it will fail the build whenever any error occures, but let warnings slip.
For testing, tere will be several levels. Unittest library for unit tests (surprise surprise), pytest for API level, and then we will sure have
some end-to-end tests as well. For this, we could use Robot framework. Probably, using one of them -- either Robot framework or pytest -- for both API testing and end-to-end, will be more efficient.
For bulding, we assume we will need this step only if we have some static files to pack, e.g. some CSS preprocessors.

As to CI/CD alternatives, there are also Gitlab Ci and Bitbucket.

Considering we are only a 6 people group, we do not have anything running in production yet, and we just want to deliver our app to public, it seems more wise to use whatever is faster to configure and easier to use. Cloud-based environment seems to be more suitable for this. The information that will help us to set up would be the prices for the runs/builds for the existing solutions.
