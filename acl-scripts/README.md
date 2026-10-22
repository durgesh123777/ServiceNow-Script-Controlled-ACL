# ACL script and configuration notes

`read_acl_script_observed.js` is transcribed from the screenshot provided in this conversation. It is a reference copy, not automatically deployed code.

Important: this script checks roles only. It does not inspect the record's `Branch` field. The project guide describes `Branch = EEE` as a condition, so verify that the condition is configured separately and saved on the intended ACL. Also inspect whether `Requires role` duplicates the role check in the script.

ServiceNow ACL evaluation can involve multiple table-level and field-level ACLs. Validate effective behavior with actual test accounts.
