# Alibaba Sentinel

Alibaba Sentinel is a powerful open source flow control component enabling reliability, resilience, and monitoring for microservices. Originally developed by Alibaba and used in production for over 10 years, Sentinel provides flow control, traffic shaping, concurrency limiting, circuit breaking, and system adaptive overload protection.

Sentinel integrates with major frameworks including Spring Cloud, Dubbo, gRPC, Apache RocketMQ, and Servlet. It provides a real-time monitoring dashboard for visualizing metrics and configuring rules dynamically. The project is written primarily in Java with a Go implementation (sentinel-golang) also available.

## APIs

- **[Sentinel Dashboard API](https://sentinelguard.io/en-us/docs/dashboard.html)** - REST interface for real-time monitoring and dynamic rule configuration

## OpenAPI Specs

- `openapi/sentinel-dashboard-api.yml` - Sentinel Dashboard REST API

## JSON Schemas

- `json-schema/flow-rule.json` - Schema for flow control rules
- `json-schema/degrade-rule.json` - Schema for circuit breaker/degrade rules

## Links

- [Website](https://sentinelguard.io/)
- [Documentation](https://sentinelguard.io/en-us/docs/introduction.html)
- [GitHub - Sentinel (Java)](https://github.com/alibaba/Sentinel)
- [GitHub - sentinel-golang](https://github.com/alibaba/sentinel-golang)
- [Wiki](https://github.com/alibaba/Sentinel/wiki)
- [Releases](https://github.com/alibaba/Sentinel/releases)
