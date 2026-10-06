# Lab 31 — Listener Sketch

## Step 1 — Method outline

in this notes file.: `@KafkaListener(topics="crm.customer-events.v1", groupId="crm-notifications")` void onCustomerEvent(...).

## Step 2 — Second group

Sketch the audit listener with groupId `crm-audit` on the same topic.

## Step 3 — Payload type

Decide: start with `String`/`JsonNode` or a typed `CustomerEvent` DTO — pick one and justify in one line.

## Step 4 — Correlation

Note where you will log `correlationId` / `lab-request-001` for support.

## Scope
Pre-lab only — do not finish the full lab in this exercise.
