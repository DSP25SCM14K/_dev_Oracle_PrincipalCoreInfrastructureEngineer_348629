# Dev Kumar — Principal Core Infrastructure Engineer Portfolio

A responsive, buildless portfolio for Dev Kumar. Open `index.html` locally or deploy the repository to GitHub Pages. The included Actions workflow publishes the static site on pushes to `main`.

## Contents

- OCI-inspired generated background artwork, with subtle motion.
- Interactive reliability-control-loop diagram and project filters.
- The full experience section from the supplied resume.
- Source links for all 22 supplied projects; demo links are included only where supplied.
- Research, education, and contact links.

## Research context

The content and visual direction were informed by Oracle's Principal Core Infrastructure Engineer posting [346035](https://careers.oracle.com/en/sites/jobsearch/job/346035), which emphasizes distributed-system architecture, scaling, fault tolerance, in-service upgrades, SLOs, telemetry, failure testing, operational readiness, incident response, safe rollback, security, and technical mentoring. The resume's measured production outcomes provide the portfolio's evidence and are presented without adding new claims.

Oracle's published infrastructure context includes isolated availability domains and fault domains designed to limit shared failure impact ([OCI regions and availability domains](https://docs.oracle.com/en-us/iaas/Content/General/Concepts/regions.htm), [OCI regions](https://www.oracle.com/cloud/public-cloud-regions/)). The latest quarter reported in the research, Q1 FY27, showed IaaS revenue of $7.4 billion, up 121% year over year; Oracle also reported delivery of 850 MW of additional datacenter capacity ([Oracle investor release, September 10, 2026](https://investor.oracle.com/investor-news/news-details/2026/Oracle-Announces-Q1-Results-Driven-by-Triple-Digit-Growth-in-Cloud-Infrastructure-Revenues/default.aspx)). Oracle's October 27, 2026 OCI direction highlights accelerator choice, faster resilient data paths, and higher utilization across AI compute ([Oracle OCI strategy, October 27, 2026](https://www.oracle.com/news/announcement/blog/ai-world-building-the-next-decade-of-oracle-cloud-infrastructure-2026-10-27/)).

## Deployment

The `pages.yml` workflow uses GitHub Actions to deploy the repository root. In the target repository, enable GitHub Pages with **GitHub Actions** as the build and deployment source if it is not already configured.
