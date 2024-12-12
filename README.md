# Wazuh - Rules

In addition to the decoder we previously created, we also need some rules, so alerts can be generated, go to
https://localhost:4343/app/rules#/manager/?tab=ruleset and add the following rules from file 
[resilmesh_rules.xml](./resilmesh_rules.xml)

To test the rule, if you want, best way to do it is by repeating the same previous test we did with the decoder.
## Correlation Rules
Some additional rules for correlation you can also add from file [resilmesh_correlation_rules.xml](./resilmesh_correlation_rules.xml)

Follow the manual if you need more specific rules: https://documentation.wazuh.com/current/user-manual/ruleset/ruleset-xml-syntax/rules.html