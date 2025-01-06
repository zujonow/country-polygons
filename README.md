# Custom Name Integration

This guide explains how to add custom region/province names using the `nameAlt` key in the properties object. This approach allows you to define and manage multiple alternative names effectively.

---

## How to Add Custom Names

To add custom region/province names, use the `nameAlt` key in the properties object. If you need to include multiple names, separate them using a pipe (`|`) symbol.

### Example Usage

```javascript
const properties = {
  nameAlt: "RegionName1 | RegionName2 | RegionName3"
};
