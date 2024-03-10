# Mindset

There are 3 whys(at company level)

What problem are we trying to solve?
Who do we solve it for?
Why are we solving this problem?

What problem are we trying to solve eg answers:
- access control and permissions
- software lifecycles
- infrastructure
- developer experience
- etc

Developers must be enjoying themselves to be able to build a great product.

Who do we solve this for eg answers(devops end users):
- developers
- quality assurance
- it (should be integrated with devops for automation)
- etc

Why are we solving this problem?
- Organization needs
- Organization unit needs(produc/service/clients)

## Organization problems

- Role based access # No Individual has access to something directly! Always use groups!
- Domains && DNS # Use Private DNS! Split Internal and External traffic! 
- Networking # How people are gonna work? Private && Public networks! Firewalls and VPN! It should be simple for end users!!
- Compute/Storage/etc # Azure? AWS? standardize?

## Developer problems

Developers ONLY deal with code and mechanisms to deploying it.

- source control
  - repository management
  - branch protections && policies # Lock down main
  - code reviews && approvals

Developers MUST have standardized procedures to manage code efficiently. Work together with developers to figure out what they like.


- service management
  - configuration
  - provisioning

Developers EMPOWERED to manage their own services.

We dont want DevOps channel to become Support Channel for company.

Brings ownership into the team, no more we got features out, but when do we deploy?


- continuous integration
  - building artifacts # Are these Docker images? Binaries?
  - testing changes # Developers testing locally!! Make pipelines fast!
  - code coverage # Gives Developers ownership of the quality of their code
  - code quality # Formatters? Linters?

Developers MUST have depenable and reliable pipelines.

- continous delivery
  - deploying artifacts # Developer ownership, have bi monthly calls in which we have sessions on deploying services together
  - environment releases

DevOps builds the system for deployments but developers own the actualy deployments.

Developers EMPOWERED to deploy their own services.

Why is developer empowerment important?
- faster development cycles
- faster feedback loops
- faster time to market
- faster time to value

DevOps must empower developers to be successful.

Saves time and money.

- logging and Metrics

We want developers to find logs and metrics.

I pushed something and it's broken, and i have no idea how it's broken. We don't want this. Have you checked the logs?

Key takeaways:

Give tools to developers to be more successful.
DevOps is a limited resource shared across the company.
Keep separation of responsabilities.
