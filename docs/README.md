# Postman Collection For VCD API

This is a postman collection & environment variables for testing vcd API. The entry for this repo is to create a new VM by utilising vcd API.

## Installation

The following tools need to be installed first before running the testing:

- [Postman](https://www.postman.com/)
- [NodeJS](https://nodejs.org/en/download/)
- [Newman](https://www.npmjs.com/package/newman)

## Getting started

After installing all the required tools, please checkout this repo and import collection and environment json file to Postman by following below steps:

1. Navigate to Collections in left panel
1. Import the collections in collections folder
1. Navigate to Environments in left panel
1. Import the environments in environments folder
1. Run the collection

Before sending the request, please make sure those environment variables are entered correctly:

- `vcd_api_host` : Vcd Api Endpoint from external portal.
- `vcd_username`: Vcd full username from external portal.
- `vcd_password`: Vcd password (same as external portal password).
- `vm_name`: For running delete_vm collection.

Optional Parmater:

- `vm_power_on`: Off as default when creating a new vm, set it to `true` in order to make it powered on.

## View Collection in Postman

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/21829237-1ef63047-c2b5-45ca-a34c-d19dc7a73e10?action=collection%2Ffork&collection-url=entityId%3D21829237-1ef63047-c2b5-45ca-a34c-d19dc7a73e10%26entityType%3Dcollection%26workspaceId%3D90fa8db2-e253-4348-b155-850d54069405#?env%5BvCloud%20Director%20API%5D=W3sia2V5IjoidmNkX2FwaV9ob3N0IiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCJ9LHsia2V5IjoidmNkX2FwaV9rZXlfdHlwZSIsInZhbHVlIjoiQmVhcmVyIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQifSx7ImtleSI6InZjZF9hcGlfdmVyc2lvbiIsInZhbHVlIjoiMzYuMiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0In0seyJrZXkiOiJ2Y2RfdXNlcm5hbWUiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0In0seyJrZXkiOiJ2Y2RfcGFzc3dvcmQiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJzZWNyZXQifSx7ImtleSI6InZjZF9hY2Nlc3NfdG9rZW4iLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJhbnkifSx7ImtleSI6InZkY191cmwiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0In0seyJrZXkiOiJzdG9yYWdlX3Byb2ZpbGVfdXJsIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCJ9LHsia2V5IjoidmRjX3VybiIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQifSx7ImtleSI6InZkY19jb21wdXRlX3BvbGljeV91cm4iLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0In0seyJrZXkiOiJ2bV9uYW1lIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiYW55In0seyJrZXkiOiJ2bV9wb3dlcl9vbiIsInZhbHVlIjoiZmFsc2UiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiYW55In0seyJrZXkiOiJ2YXBwX3RlbXBsYXRlX3VybCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImFueSJ9LHsia2V5IjoidmFwcF90ZW1wbGF0ZV9uYW1lIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiYW55In0seyJrZXkiOiJ2YXBwX3RlbXBsYXRlX3VybiIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImFueSJ9LHsia2V5Ijoidm1fdXJsIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiYW55In0seyJrZXkiOiJ2bV9zdGF0dXMiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJhbnkifV0=)

## References

For more information about VCD API, please check the official link below:

- [VCD Open API](https://developer.vmware.com/apis/vmware-cloud-director/v36.2/)
- [VCD Schema Reference](https://developer.vmware.com/apis/1232/vmware-cloud-director/doc/about.html)
