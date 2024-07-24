# Kuadrant Governance

At the time of writing, Kuadrant is a single-company project (Red Hat).
All maintainers are Red Hat employees.
Roles and rules around who can merge & review code and documentation are loosely governed.
There are multiple technical leads in the project, without any one clear project leader.
This will likely change as the project builds an external community and requires more transparent and accessible ways for people to engage and become members of the community.

## Roles

### Maintainers

The list of maintainers for the project is at [./MAINTAINERS.md](./MAINTAINERS.md).
Generally, these people have the ability to create, approve and merge pull requests on any repository.
As it stands, a Red Hat employee that is assigned to the Kuadrant project will be assinged a maintainer role.

### Component specific maintainers

Some components have a subset of maintainers. The list of components and maintainers can be found in the [./MAINTAINERS.md#component-specific-maintainers](./MAINTAINERS.md#component-specific-maintainers) section.
These people have the same permissions as maintainers.
However, their role includes having domain expertise in those components.
They can be thought of as technical leads in a smaller part of the overall project.
There are no set rules for how a person can move from a maintainer role to a component specific maintainer role.
Generally, if a person is sufficiently active in a particular area, they may add themselves, be added, or request to be added to the list for a component.

### De facto project leads

Although the project doesn't have a lead person, there are a few people that have become de facto leads.
They would tend to be the most active on disucssions around roadmap items, releasing and generally on the community call.
They would also be the main people that others would look to for approval on changes.
The are:

- Alex Snaps [alexsnaps]
- Craig Brookes [maleck13]
- Eguzki Astiz Lezaun [eguzki]
- Guilherme Cassolato [guicassolato]

There are no set rules for how a person can move to a 'de facto project lead' role.
The existing list of people is subjective, based on who has been involved from the early stages of the project, and continues to be involved in the ways mentioned above.

## Decision making

How decisions are made can be somewhat subjective.
Depending on the impact size of the decision, what components it touches or if it changes the API, a different approach made be used.
Here are some examples of how decisions have been made in the past:

- discussing openly on the community slack channel
- a call with a specific group of people (like component specific maintainers or a 'de facto project lead')
- discussing on the community call
- discussing in comments on a pull request
- [writing an RFC](https://github.com/Kuadrant/architecture/tree/main?tab=readme-ov-file#kuadrant-rfcs) (generally used for "adding new features or introducing breaking changes in the Kuadrant stack")

## Releasing

The Kuadrant release process is defined in this [RFC](https://github.com/Kuadrant/architecture/blob/main/rfcs/0008-kuadrant-release-process.md).
