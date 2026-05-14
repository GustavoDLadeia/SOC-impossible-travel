# Suspicious Login (Impossible Travel)

Scenario involving a possible suspicious login identified through an impossible travel pattern, with consecutive access attempts from the same user in different countries within a short time interval. The geographical discrepancy without the use of an authorized VPN indicates a strong sign of credential compromise.

## Summary

Consecutive logins from the same user were identified originating from geographically  
distinct locations within a short time interval, indicating possible account compromise.

## Evidence

- User: `ana.ferreira`
- Login 1: Brazil — `10:15 AM`
- Login 2: Germany — `10:22 AM`
- Interval between logins: 7 minutes
- Absence of authorized VPN usage

## Analysis

The short interval between logins from geographically distant locations characterizes a  
typical "impossible travel" pattern, incompatible with physical displacement.

The absence of authorized VPN records reduces the likelihood of legitimate activity.  
However, the use of an unauthorized VPN or proxy cannot be completely ruled out.

This type of behavior is frequently associated with the misuse of credentials  
compromised by third parties.

There is no evidence, within the analyzed context, that justifies legitimate activity for this  
access pattern.

- Severity: High
- Confidence: High

## Conclusion

Highly suspicious activity consistent with account compromise.

## Action

- Force password reset for the user
- Revoke active sessions
- Validate with the user whether the access was legitimate
- Verify the origin of the involved IPs
- Monitor for new suspicious logins
- Escalate to N2 if the behavior persists
