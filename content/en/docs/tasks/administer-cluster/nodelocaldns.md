---
reviewers:
- bowei
- zihongz
title: Using NodeLocal DNSCache in Kubernetes clusters
content_template: templates/task
---

{{% capture overview %}}
This page provides an overview of NodeLocal DNSCache feature in Kubernetes.
{{% /capture %}}

{{% capture body %}}

## Introduction

### Feature availability

The addon can be applied using the yaml specified in any k8s version. The feature support is as described:

| k8s version | Feature support |
| :---------: |:-----------:|
| 1.15 | Beta |
| 1.13 | Alpha |
