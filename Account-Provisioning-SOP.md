# Identity and Access Management (IAM) Case Study: User Provisioning Workflow

## Project Purpose

This simulated Standard Operating Procedure demonstrates my understanding of identity and access management (IAM), user provisioning workflows, role-based access control (RBAC), and security-focused documentation practices.

The goal of this document is to demonstrate how clear procedures help maintain secure, consistent, and auditable account management processes.

## Security Concepts Demonstrated

This project demonstrates understanding of:

- Identity and Access Management (IAM)
- Role-Based Access Control (RBAC)
- Least privilege principles
- Access validation
- Audit documentation
- Secure onboarding workflows

## Document Control

- **Document ID:** SOP-IT-004
- **Version:** 1.0
- **Classification:** Portfolio Simulation
- **Document Creator:** Sullivan R. Kerns
- **Exercise Type:** Simulated IT Operations Documentation

## 1. Purpose & Scope
This procedure demonstrates the process of securely creating user accounts, assigning appropriate permissions, and maintaining accurate access records.

## 2. Pre-Provisioning Data Integrity Checks
Before generating credentials or allocating system permissions, the technical analyst must execute a manual audit of the inbound identity file to eliminate data discrepancies:
1.  Cross-reference the inbound provisioning request parameters with the official HR source system record to verify exact spelling, employee ID metrics, and department codes.
2.  Audit the target system architecture to confirm that the requested username pattern does not trigger a duplication error or overwrite existing database lines.
3.  Isolate any formatting deviations or data mismatches. If data irregularities are identified, halt the sequence and route a tracking ticket notes log back to the originating department queue.

## 3. Step-by-Step Provisioning Sequence
The analyst must methodically step through the configuration process using established technical runbooks:

### Phase A: Directory & Profile Initialization
*   **Step 1:** Log into the centralized directory infrastructure interface using secure authentication protocols.
*   **Step 2:** Select the designated Organizational Unit (OU) matching the verified employee department parameters.
*   **Step 3:** Initialize a new user profile container. Input parameters precisely: `First Name`, `Last Name`, `Primary Email Interface Pattern`, and `Unique Employee Metric ID`.

### Phase B: Role-Based Access Control (RBAC) Assignment
*   **Step 1:** Map the profile container strictly to predefined enterprise security group arrays based on role profiles.
*   **Step 2:** Apply least-privilege baseline configurations. Do not grant administrative or systemic write permissions unless explicitly authorized by an identity governance sign-off sheet.
*   **Step 2a (Trial-and-Error Validation Check):** Verify group inheritance behaviors manually. If group flags cascade incorrectly or generate conflicting permissions, clear the container parameters, review the access logs, and rebuild the profile properties line-by-line to reach consistency.

### Phase C: Cloud Integration (AWS / Azure Alignment)
*   **Step 1:** Push the directory profile updates to federated cloud environments using automated system connectors.
*   **Step 2:** Audit the cloud console management layer to confirm successful profile replication and ensure that identity token paths are communicating without timeout anomalies.

## 4. Quality Assurance & Logging Compliance
*   **Generate Completion Log:** Upon successful initialization, execute a manual access check on the newly built container to ensure execution matches expected operational behaviors.
*   **Audit Trail Retention:** Log a comprehensive written resolution summary within the internal technical ticketing system. Archive the completion metrics, timestamp details, and provisioning configuration references for compliance auditing schedules.

## 5. Account Deprovisioning Considerations

When an employee leaves the organization:

1. Disable user authentication access.
2. Remove group memberships and assigned permissions.
3. Review active sessions and connected applications.
4. Preserve required audit records.
5. Confirm completion through documented verification.
