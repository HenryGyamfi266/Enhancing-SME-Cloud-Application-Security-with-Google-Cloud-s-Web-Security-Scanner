# Enhancing-SME-Cloud-Application-Security-with-Google-Cloud-s-Web-Security-Scanner
## In this project, I run a security scanner on SMEs apps making sure they are secured.
The Web Security Scanner, one of Security Command Center's built-in services, identifies security vulnerabilities in my Google App Engine, Google Kubernetes Engine (GKE), and Compute Engine web applications. It crawls my application, following all links within the scope of my starting URLs, and attempts to exercise as many user inputs and event handlers as possible.

The scanner is designed to complement my existing secure design and development processes. To avoid distracting me with false positives, the scanner errs on the side of under-reporting and will not display low-confidence alerts. It does not replace a manual security review, nor does it guarantee that my application is free from security flaws.
