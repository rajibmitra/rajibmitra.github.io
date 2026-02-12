---
layout: default
---

# Welcome to My Blog

Hi! I'm Rajib, a passionate software engineer sharing insights about technology, coding, and my learnings.

## Latest Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

## About Me

Currently working as a Staff Software Engineer at Okta, I specialize in architecting authentication and authorization services in multi-cloud environments spanning GCP and AWS. My work focuses on leveraging technologies such as Kubernetes, Crossplane, and GitOps to enable automated resource provisioning and ensure resilient worldwide service deployment. 

With expertise in hybrid cloud infrastructures and observability practices, I contribute to building scalable and high-performing platforms capable of managing over a billion requests per second. I am committed to advancing infrastructure automation and delivering solutions that prioritize reliability, operational efficiency, and seamless integration across diverse cloud ecosystems.

[View My GitHub](https://github.com/rajibmitra)

## Resume

You can view or download my resume here:

- [Open Resume](/assets/Rajib_Mitra_Resume.pdf){:target="_blank"}
- [Download Resume](/assets/Rajib_Mitra_Resume.pdf){:download="Rajib-Mitra-Resume.pdf"}
