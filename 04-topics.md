---
layout: page
title: Topics
permalink: by-topic/
comments: true
---

Common threads within government include:

* Building a unified data platform.
    * A\*DAX (I2R, A*STAR)
    * data.gov.sg (iDA GDS DSG)
    * URA ePlanner
    * [iDA Smart Nation Platform](https://www.ida.gov.sg/~/media/Files/About%20Us/Newsroom/Media%20Releases/2014/0617_smartnation/AnnexA_sn.pdf)
* Agile workflow - iterate, learn and fail fast.
    * MOE ESTL
    * iDA GDS
    * *[Challenges facing agile workflow adoption in Asia - Medium](https://medium.com/software-craftmanship/scrum-does-not-work-here-in-asia-72d7bccccb4d).*
* Building data analytics capabilities and assembling a team of data scientists.
    * [I2R Data Analytics Dept](http://datam.i2r.a-star.edu.sg/)
    * IHPC Computing Science ([CDA](http://www.a-star.edu.sg/ihpc/Research/Computing-Science-CS/Cross-disciplinary-Data-intensive-Analytics-CDA-Group/Overview.aspx) and [Complex Systems](http://www.a-star.edu.sg/ihpc/cxsy))
    * iDA GDS Data Science Group
* Talent management
    * Emphasis on hiring and grooming top-tier software engineering talent.
        * MOE ESTL
    * Why it is important to hire the best
        * An organisation is less willing to tolerate incompetence or poor team players when they are paying more for them.
        * Top tier software engineers are good value for money, since the value of a team is affected significantly by its weakest member (stronger members need to spend time mentoring inexperienced members, and cleaning up the mess of weak members.)
        * An organisation that is not willing to pay for good engineers or support engineers' personal growth will see their top people leave, bringing others along with them (since people want to work with the best people).
    * Hiring tips
        * [Engineering Management - Hiring, Wong Yishan (ex-Facebook CTO, ex-Reddit CEO)](http://algeri-wong.com/yishan/engineering-management-hiring.html)

        > A players hire A players, B players hire C players and C players hire D players. -- Steve Jobs.
    * Need to avoid traditional policies where organisations promote their best engineers into management and policy work, leaving only incompetent engineers behind
    * Need to avoid traditional view that software engineering is a low-level job that is easily outsourced and that software engineers are simply 'code monkeys'
* Educating management on technical CS details.
    * [Blog on Machine Learning for the layman](https://annalyzin.wordpress.com/) by a group of MINDEF employees
    * *UK*: [Guide for CTOs](https://www.gov.uk/service-manual/chief-technology-officers) by UK GDS
* Views on outsourcing and contracting out software development. The need for inhouse expertise.
    * Avoiding getting overcharged by contractors and taken for a ride
        * Divergence in motivations, with contractors maximising profit and inhouse engineers optimising for service and 'doing the right thing'
        * Inhouse engineers are incentivised to invest in infrastructure and maintainable code that will save them work in the long run. Software is built with an eye for the long term, rather than for the purpose of hitting a contract deadline or generating a press release.
    * View contractors as a force multiplier, rather than providing expertise not available inhouse.
        * Inhouse software engineers should be technically capable of implementing it themselves if needed to or given adequate time.
        * This avoids the situation where there is no inhouse expertise to assess the quality of the product delivered.
        * This aims to avoid the common practice where a contractor submits a low-priced bid, wins the tender, and produces a sub-par product that barely meets specifications and fails in the fundamental goal. The contractor then makes further money by making it expensive to submit change requests, claiming that they are beyond the original specification. Even if the government wishes to LD the contractor into insolvency, the public still ends up with a poorly-implemented, unmaintainable and unextensible mess of spaghetti code which quickly breaks down and needs to be replaced prematurely, starting the procurement process again.
        * Lack of sufficient testing results in D-day production nightmares.
    * Acceptance testing should be implemented at the code level with an inhouse software engineer reviewing the code as it is written, instead of making it outcome-based when the product has already been completed and only minor modifications are possible.
        * The contractor's process and progress should be continuously assessed, and problems caught right when they are introduced into the codebase when they can be fixed.
    * Long procurement cycles are hard to reconcile with an iterative and agile model of software development.
    * MOE ESTL
    * GTA GDS
* Empowering SWEs with solid infrastructure.
    * Code review tools: [Phabricator](http://phabricator.org/), [GitLab](https://about.gitlab.com/)
    * Self service analytics and ops dashboards.
    * Code search tool e.g. [livegrep](https://github.com/livegrep/livegrep)
    * Universal search that combines code search, internal wiki search, Slack/IRC messages, etc.
    * Automated testing
        * Unit testing frameworks (with shimming, where appropriate).
        * End-to-end integration tests.
        * Browser automation tests (e.g. [Selenium](http://www.seleniumhq.org/))
    * Data analytics infrastructure.
* Importance of an engineering-driven decision making culture.
* Smart Nation
    * The successor to iN2015, Smart Nation describes a better Singapore made possible through greater access to data, greater citizen participation in government and a government that leverages technology capabilities to better serve citizens.
    * It is a major impetus driving the need for inhouse software engineering expertise in order to best leverage opportunities made possible through the application of computer science.
    * It is coordinated by SNPO, PMO and supported by iDA, A\*STAR and other agencies.
    * [Lee Hsien Loong's speech launching Smart Nation, 24 Nov 2014](http://www.pmo.gov.sg/mediacentre/transcript-prime-minister-lee-hsien-loongs-speech-smart-nation-launch-24-november)
    * [SNPO Smart Nation site](http://www.pmo.gov.sg/smartnation)
    * [iDA Smart Nation site](https://www.ida.gov.sg/smartnation)
    * [Forbes microsite](http://www.smartnation-forbes.com/)
{% include common.md %}
