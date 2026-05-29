<div align="center">
  <a href="https://www.namastack.io">
    <img src="https://raw.githubusercontent.com/namastack/namastack-web/main/public/namastack_logo.png" alt="Namastack" width="150" />
  </a>

  <h1>Namastack</h1>

  <p><strong>Reliable foundations for event-driven systems.</strong></p>
  <p>Open-source infrastructure tools for modern distributed applications.</p>

  <p>
    <a href="https://www.namastack.io">Website</a>
    ·
    <a href="https://www.namastack.io/outbox">Documentation</a>
    ·
    <a href="https://github.com/namastack/namastack-outbox">Namastack Outbox</a>
    ·
    <a href="https://github.com/sponsors/namastack">Sponsor</a>
  </p>

  <p>
    <a href="https://github.com/namastack/namastack-outbox/actions/workflows/gradle-test.yml">
      <img src="https://github.com/namastack/namastack-outbox/actions/workflows/gradle-test.yml/badge.svg" alt="Namastack Outbox CI" />
    </a>
    <a href="https://javadoc.io/doc/io.namastack/namastack-outbox-core">
      <img src="https://javadoc.io/badge2/io.namastack/namastack-outbox-core/javadoc.svg" alt="Javadoc" />
    </a>
    <a href="https://opensource.org/licenses/Apache-2.0">
      <img src="https://img.shields.io/badge/License-Apache_2.0-blue.svg" alt="Apache 2.0 License" />
    </a>
  </p>
</div>

---

## What We Build

Namastack builds reliable infrastructure primitives for distributed systems, with a focus on Spring Boot, event-driven architecture, and production-grade messaging workflows.

Our first major project is **Namastack Outbox**, a transactional outbox engine that helps teams keep database changes and published events consistent without adding unnecessary operational complexity.

## Featured Project

<table>
  <tr>
    <td width="35%"><strong><a href="https://github.com/namastack/namastack-outbox">Namastack Outbox</a></strong></td>
    <td>Transactional outbox support for Spring Boot applications, built for reliable event delivery, retries, ordering, observability, and production operations.</td>
  </tr>
  <tr>
    <td><strong><a href="https://www.namastack.io/outbox">Documentation</a></strong></td>
    <td>Guides, configuration reference, database setup, messaging integrations, observability, and examples.</td>
  </tr>
  <tr>
    <td><strong><a href="https://github.com/namastack/namastack-web">Website</a></strong></td>
    <td>The Namastack website and project landing page.</td>
  </tr>
</table>

## Why It Exists

Distributed systems fail in places that look harmless on paper: one database write, one event publish, one retry, one crashed instance. Namastack focuses on the reliability layer around those boundaries.

We care about:

- **Consistency** between application state and emitted events
- **Reliable delivery** with retries, ordering, and failure handling
- **Operational clarity** through metrics, tracing, and predictable behavior
- **Spring Boot ergonomics** with clean auto-configuration and familiar APIs
- **Open development** with practical documentation and examples

## Ecosystem

Namastack Outbox supports Java and Kotlin applications running on Spring Boot, with modules for relational databases, MongoDB, messaging integrations, observability, and production operations.

Core areas include:

- Transactional outbox pattern
- Event-driven microservices
- Spring Boot auto-configuration
- Spring Modulith event externalization
- Kafka, RabbitMQ, and AWS SNS integrations
- Micrometer metrics, tracing, and Actuator support

## Get Involved

- Read the docs: <https://www.namastack.io/outbox>
- Open an issue: <https://github.com/namastack/namastack-outbox/issues>
- Start a discussion: <https://github.com/namastack/namastack-outbox/discussions>
- Support development: <https://github.com/sponsors/namastack>

---

<div align="center">
  <sub>Built by Namastack for teams that need distributed systems to behave predictably.</sub>
</div>
