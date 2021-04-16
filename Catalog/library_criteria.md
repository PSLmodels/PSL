
PSL Project Criteria
============================================

Summary
-------

1. Models must be transparent.
1. Interface recommendations facilitate interoperability.
1. Organizational recommendations facilitate community.

Introduction
-------------

Open-source modeling ensures that model results are reproducible, that experts around the world can collaborate to make models better, and that users can explore the parameter space for themselves. These outcomes systematically improve public policy decisionmaking.

We have developed the criteria in this document to facilitate the growth of an open source public policy modeling ecosystem.

Criteria
---------
PSL establishes three kinds of project Criteria. A project are required to (`MUST`) conform to `Acceptance Criteria` to be accepted in PSL. Projects are recommended to (`SHOULD`) or optionally (`MAY`) conform to various `Community Criteria` and `Interoperability Criteria`.

Acceptance Criteria for Transparency and Quality
--------------------------------------------

1. Models MUST be released under an OSI-approved open source license or the Creative Commons Public Domain Dedication (CC0).
1. Data MUST be publicly available, unless release is restricted by a third party.
1. For any data that SHOULD not be disclosed, provided MUST be:
	- A complete descriptive list of all data variables;
	- Descriptive statistics for all data variables for such data (including averages, standard deviations, number of observations, and correlations to other variables), to the extent that the descriptive statistics do not violate the rule against disclosure;
	- Contact information for the individual or entity who has unrestricted access to the data.
1. Projects MUST have unit tests and SHOULD report code coverage.
1. At least one test MUST generate key outputs from source materials, the test MUST be run with every new version, and the outputs of the test MUST be checked into the repository.
1. Projects MUST report names and contact information for at least one maintainer.
1. Projects MUST have a suggested citation.
1. Projects MUST have a project overview.
1. Projects MUST have installation directions.
1. Project MUST be mirrored in the same GitHub organization as PSL, and therefore they MUST be under version control.
1. Projects MUST use a consistent versioning scheme, which SHOULD be [semantic versioning](https://semver.org/).

Community Criteria
-------------------

1. Projects SHOULD have a public roadmap.
1. Projects SHOULD have contributor documentation and guidelines.
1. Projects SHOULD have regular office hours, webinars, or standing meetings.
1. Projects SHOULD list technical contributors.
1. Projects SHOULD list funders.
1. Projects SHOULD list user citations and case studies.
1. Projects SHOULD include a disclaimer.
1. Projects SHOULD have a public issues tracker.
1. Projects SHOULD have a changelog.
1. Projects SHOULD adopt a consistent code formatting scheme. Projects MAY use an automated code formatter like [Black](https://black.readthedocs.io/en/stable/).
1. Projects MAY have a Stack Overflow channel.
1. Projects MAY include a "News" translation of the changelog for users.
1. Projects MAY include criteria for participating in cross-model PSL initiatives.
1. Projects MAY include a link to a webapp version.
1. Projects MAY include a list of consultants.


Interoperability Criteria
--------------------------

1. The source code SHOULD be written in an open source language.
1. A `PSL_catalog.json` configuration file to be used for cataloging these criteria MUST be included in the project's repository. Specific instructions for creating this file can be found in the [Catalog-Builder Documentation](https://github.com/PSLmodels/PSL-Infrastructure/tree/master/Tools/Catalog-Builder#how-to-add-projects-to-the-catalog).
