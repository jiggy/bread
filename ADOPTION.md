# Adopting Bread

Bread License pre-1.0 gives free personal use, qualifying business use, and evaluation,
with company-wide purchases for larger businesses. A purchase provides lasting
rights to covered releases and at least twelve months of new official releases.
The [license](LICENSE.md) fixes the bargain; this guide explains how to adopt it.
The [fictional example](EXAMPLE-ADOPTION.md) includes its own illustrative
price schedule and grants no rights.

## Is it suitable?

Use Bread when you want to sell permission for one complete software product,
keep individual experimentation easy, and publish a predictable business price.
It funds the designated licensing steward; it does not distribute income among
contributors or guarantee renewals. A company can buy once and maintain its
covered release or a permitted fork indefinitely.

Bread is most suitable for a deliberate selection of substantial products.
Each independently licensed dependency can create a separate company purchase.
A common name does not combine sellers, prices, or entitlements. A downstream
builder must be able to identify those combined obligations before distribution.
There are no royalties to Bread, required membership, or shared billing service.

## Text reuse and the Bread name

Permission is granted to anyone to copy, reproduce, translate, adopt, adapt,
and distribute the Bread license text and adoption materials freely, including
for commercial purposes. No fee, royalty to the Bread initiative, membership,
registration, or individual approval is required. This permission applies now,
including to earlier review drafts; it does not grant rights in software that uses
or illustrates the model.

You may identify an instrument as **Bread License** with its applicable version
or draft identifier only when its standard English license text is reproduced
unchanged. The following are permitted without changing that name:

- Supply the identifying facts and commercial choices expressly permitted by
  that version in a separate adoption notice, order, or schedule.
- Offer separately labeled additional permissions that expand rights without
  restricting or replacing the underlying Bread grants.
- Change layout or formatting while preserving every word, punctuation mark,
  provision, and their order.

Any other change to the standard text requires a distinct license name, not
**Bread** or **Bread License**, and an explanation of the changes. This includes
rewriting a clause even if you believe its meaning is equivalent. You may
describe the result as **“based on Bread License [version]”**, but must not
present it as that Bread License version.

Translations may accompany the unchanged English text as clearly labeled,
non-authoritative explanations. An independently authoritative translation is
a modified instrument and must use a distinct license name under this policy.

Permission to adapt the text does not imply endorsement of the result. This
naming policy makes no claim of trademark registration.

## Fixed rules and adopter choices

| Category | Content |
| --- | --- |
| Fixed bargain | US$1m consolidated Annual Revenue threshold; personal and evaluation grants; Group scope; at least twelve-month Update Terms; permanent covered-release rights; distribution, hosting, source, supplier-purchase and continuity rules |
| Commercial choices | Published prices, revenue bands above the free threshold, billing currency, offered Update Terms of at least twelve months, and express credit arrangements |
| Identifying facts | Software scope, Licensor, authorized sellers, working contacts, official release records, retained license and dated price schedule |
| Adopter duties | Possess grant authority; publish an ordinary purchase route; preserve accepted terms and release records; issue customer confirmations; provide corresponding source when distributing; honor acquired rights and the continuation grant |

Prices can differ among adopters. Shorter paid terms, corporate runtime rental,
a customer royalty, a competing-product prohibition, or narrower free eligibility
would change the standard license, rather than fill a pricing field. Identify a
modified instrument under a different name. Additional grants may expand rights
if clearly identified. Support and sponsorship are separate commercial offers;
they do not change Bread's purchased permissions or minimum term.

## Set up the ordinary path

1. **Identify what you can license.** Preserve third-party terms and ensure
   contributors and sales operators supply sufficient authority, including for
   accepted future-release commitments and the continuation grant. Bread requires no particular
   contribution agreement or governance.
2. **Supply the notice, exact text, and prices.** A monitored email address,
   ordinary invoices, and retained records can implement the purchasing route.
   No portal or license-validation infrastructure is required.
3. **Preserve official releases.** Keep identifiers and first-publication times
   in UTC. Do not replace release bytes or use a major-version label to exclude
   material promised by an accepted Update Term.
4. **Issue the customer's confirmation.** The record identifies the actual
   Group, not a supplier's customers collectively. Send it directly to the
   customer and copy its purchasing supplier if applicable.

Free users and evaluators need none of these administrative steps.

### Adoption notice template

```text
Software: [family name and precise covered material]
Licensor: [legal identity, notice address, licensing capacity]
Authorized sellers: [identity and actual authority, or Licensor itself]
Licensing and notices: [working channels]
Bread text: Bread License pre-1.0 [retain exact local text]
Applies from: [identified source/release]
Official releases: [identifiers and publication records]
Separate material: [scope and location of other licenses]
Pricing: [dated schedule, currency, bands, terms of at least twelve months]
Purchase channel: [working route]
Additional grants: [none, or identified expansion]
```

An example or incomplete notice does not adopt Bread for software. An actual
adoption identifies the material and source/release from which it applies.

### Ordinary coverage record

```text
Licensor / authorized seller: [identities]
Customer Group / controlling parent: [legal identity]
Software family: [identified scope]
Annual Revenue band: [customer declaration]
Accepted terms: [retained Bread text, adoption notice, dated price schedule]
Price / taxes / payment: [amounts and receipt, or credit below]
Credit, if accepted: [authorized seller's express acceptance, debtor, due date]
Update Term: [inclusive start, exclusive end; UTC; at least twelve months]
Covered Releases: existing official releases plus releases first published
  during this term, subject to [identified existing exclusions, or none]
Official release records: [retained identifiers and publication times]
Renewal choice and cancellation route: [details]
Purchasing supplier, if any: [identity; no authority to issue this grant]
```

The order and confirmation may be one document. They do not need cryptographic
signatures, activation tokens, an employee roster, or a public customer registry.
Do not invent a second entitlement system inside the confirmation.

## Purchasing through a supplier

Suppose Northstar wants Joe's $100 application and needs a first $120 Ledger
Engine purchase under the fictional example's schedule. Joe may order from
Lantern Tools with Northstar's authorization, naming Northstar and its declared
band. Lantern receives $120, issues Northstar's company coverage, and sends
confirmation to Northstar and Joe. Joe can then invoice his application and the
upstream purchase together. Alternatively, Northstar pays upstream itself.
Joe's own entitlement cannot cover Northstar.

Joe is a purchasing intermediary, not an agent authorized to issue Ledger Engine licenses
or collect money on its behalf. Before collecting an upstream charge, he must
explain that paying Joe alone does not acquire the upstream entitlement.
He may advance the upstream payment; ordinary credit is possible only if the
upstream seller expressly accepts it. A self-written receipt cannot replace
that transaction. This does not prevent ordinary fraud, but it does not authorize
Joe to create a valid upstream license while withholding its purchase price.

Once acquired, Northstar's grant survives Joe's business failure. Another app
using the same covered Ledger Engine release requires no second purchase. An app
requiring a newer, uncovered official release may require another Update Term.
The underlying first-adoption price remains real even when Joe combines invoices.

## Distributing products and forks

Free and paid products follow the same rule: include the license, release
identification, notices, and corresponding covered source. Independently operated
business installations require their responsible Group's applicable permission.
Provider-controlled service access follows section 6, including supplied clients. The distributor does not audit customer revenue or
report receipts, and need not arrange purchases. Merely sharing copies is free;
using the software operationally in a distributor's own business follows the
ordinary eligibility or company-purchase rules.

A notice shipped with an app can say:

```text
[Application/version] includes [Software/release identifiers; modifications].
[Software] is licensed by [Licensor] under the accompanying Bread License pre-1.0.
Personal use, qualifying business use, and evaluation are free. Independent
business operation requires the responsible Group's permission for these
releases; an existing purchase for another app may cover them. Provider-controlled
service access, including supplied clients, follows section 6. Receiving a copy
does not transfer the supplier's company license. Purchases: [official channel].
Corresponding covered source and build instructions: [retainable supplied copy].
Other components: [licenses/inventory].
```

Identify a new required upstream release when distributing an update, so buyers
can assess its coverage before installing. A dependency installed separately
has the same licensing requirements as a bundled copy. Independent application
files can remain private; covered files and modifications follow section 7.

Fork modifications add no second upstream permission fee. A company covered
for release A can use subsequent independently developed modifications of A,
including successive forks. Incorporating a newer, otherwise-uncovered official
release needs applicable permission. Fork authors may charge for delivering
copies, services, or independent additions. They do not become the upstream
fee recipient by renaming the fork.

### Multiple dependencies

If three independent components each require a $1,000 company purchase, a
company needing all three pays $3,000 to three sellers. There are three coverage
records, but no application-revenue reports. That same company need not purchase
those same covered components again for a second application. Newer releases
can change coverage needs. Suppliers should identify the component inventory
and purchasing routes without pretending that a shared Bread name covers all.

## Hosting: identify the responsible deployment

| Situation | Applicable permission |
| --- | --- |
| Joe operates an independent hosted product, including free plans or customer-written workflows | Joe's Group; customers need no additional license merely for service access |
| Microsoft rents a dedicated tenant in Joe's provider-controlled service | Joe's Group; dedicated tenancy alone does not change responsibility |
| Joe administers Microsoft's deployment in Microsoft's controlled cloud account | Microsoft's Group; no second purchase merely for Joe's administration |
| Microsoft exports and independently operates a copy | Microsoft's own applicable permission |
| Anna receives a report produced by the service | No fee merely for receiving the output |

Client-side execution supplied as part of a provider-controlled service is
included even when application computation runs locally in a browser. A copy
deployed and controlled by the customer for independent operation requires its
own applicable permission.
Distributed client code still needs the corresponding source and notices.
Private server changes need not be published. A provider's departure does not
promise continued hosting; the software grant does not supply infrastructure.

## When licensing becomes unavailable

Existing grants and purchased update commitments survive immediately. Newcomers
can use free evaluation but do not automatically receive operational permission
during an outage. Section 8 supplies a pre-granted continuation permission after
180 consecutive days of ordinary purchasing unavailability, documented through
a qualifying request and a further notice at least 30 days before the end.

The continuation covers the requesting Group for releases already published
under Bread when its request was sent; source, notice, and downstream company
conditions remain. Newcomers can qualify through the same process. It survives
a later return of the seller. It covers neither future releases nor unpaid earlier
obligations. A refusal to pay, applicant-specific legal obstacle, or inactivity
in development is not abandonment. Retain the request, notice, and final
unsuccessful attempt; no public customer registry is required. Missing contacts
or prices have an evidence-based fallback. Intentional closure of sales can
trigger this rule too; adopters must understand that choice.

## Before publishing an adoption

Retain the exact Bread License pre-1.0 text and complete the adoption notice.
The [text-reuse and name policy](#text-reuse-and-the-bread-name) grants no rights
in the adopter's software and supplies no missing sales authority.

Review the actual grant authority, purchase formation, source and patent scope,
individual protection, continuation mechanism, and mandatory obligations with
appropriate professional advice. Agent scenarios test interpretation, not
legal enforceability or willingness to pay. Do not claim a required compensation
structure or recurring payment from companies merely retaining covered releases.

For software records, a locally unique `LicenseRef-Bread-pre-1.0` may identify the
extracted text and adoption facts under the [SPDX LicenseRef mechanism](https://spdx.github.io/spdx-spec/v2.3/other-licensing-information-detected/).
It is not an SPDX listing, OSI approval, or certification.
