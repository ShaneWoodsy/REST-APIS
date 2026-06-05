# Dane Food API

A production-ready REST API for managing customers, food inventory, and orders with webhook support for real-time order status notifications.

## Overview

The Dane Food API provides a complete solution for:
- **Customer Management** - Create, retrieve, update, and delete customer profiles
- **Food Inventory** - Manage food products, brands, and distribution centers
- **Order Processing** - Place orders with line items, track status via webhooks

Built with strict OpenAPI 3.0.2 specification compliance, emphasizing explicit schema validation and consistent HTTP semantics.

---

## Quick Start

**Base URL:** `https://api.gigantic-server.com`

**Authentication:** Basic Auth or JWT Bearer Token

```bash
curl -H "Authorization: Bearer <your-jwt-token>" \
  https://api.gigantic-server.com/v1/customers
```

---

## Versions

| Version | Status | Link |
|---------|--------|------|
| **1.0.0** | Stable | [View Docs](./1.0.0/) |

---

## Features

✅ **Complete CRUD Operations** - Manage customers, foods, and orders  
✅ **Pagination Support** - Built-in page number and size parameters  
✅ **Webhook Callbacks** - Real-time order status notifications  
✅ **Strict Schema Validation** - Explicit field constraints prevent integration errors  
✅ **Semantic HTTP Responses** - Proper status codes (200, 201, 204, 400, 404, 409)  

---

## Resources

- **OpenAPI Specification** - See `1.0.0/spec.yaml`
- **API Documentation** - See `1.0.0/README.md` for endpoints and examples
- **Contact** - shane@example.com

---

## Architecture Notes

This API demonstrates docs-as-code best practices:
- Hand-crafted OpenAPI schemas (not auto-generated)
- Complete Schema Object definitions with constraints
- Proper component reuse via `$ref`
- Comprehensive validation preventing downstream failures
