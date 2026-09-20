# Adopting Bread

**Draft for review.** The [Bread License](LICENSE.md) is a reusable draft.
Use this guide to assess a proposed adoption. Before making an actual offer,
resolve the publication prerequisites at the end of this guide.
The [Jig example](JIG-ADOPTION.md) uses the same procedure.

## Decide whether it fits

Bread offers three ways to get permission:

- **Free use:** personal use, use by qualifying organizations, and evaluation
  are automatically allowed. Qualifying free use requires no payment,
  contribution, promotion, or expression of gratitude.
- **Organization purchases:** organizations can buy coverage directly. Rights
  to covered releases continue if the organization does not renew.
- **Included product coverage:** an optional 1% paid-distribution agreement
  lets publishers include coverage for their customers.

When covered software is distributed, its covered source remains available.
Independent application code keeps its own license.

It is intended first for substantial software products. It is not a promise
that a stack of small separately payable dependencies is economical or simple.
Each independent licensor has its own agreement, receipts, records, and payments.
There is no shared Bread account, blanket license, pooled royalty, or initiative
fee. Before selecting dependencies, determine both the total obligations and the
permissions your customers receive.

## Keep the bargain fixed; supply the facts

The license sets the rules. Adopters choose the permitted commercial details,
identify who and what the license covers, and carry out the duties below.
Capitalized terms such as Financial Scale, Group, and Update Term keep their
exact meanings in the [license](LICENSE.md).

| Category | What belongs here |
| --- | --- |
| Fixed rules | The $1m Financial Scale boundary and definition; automatic evaluation; perpetual covered-release rights; Group scope; source obligations; standard 1% rate, receipts, reporting and product coverage; remedies and continuity. |
| Commercial choices | Published direct amounts, bands, billing currency and Update Terms; optional sponsorship and separately stated services or benefits. These cannot narrow the fixed rights or change the standard distribution rate. |
| Identifying facts | Software and covered material; actual Licensor; authorized seller; contacts; official release records; exact license and price-schedule versions. |
| Adopter responsibilities | Have authority for the grants; make purchasing and enrollment available while offers are open; deliver required source; preserve accepted terms and publication records; issue durable coverage records; honor acquired customer rights through seller changes. |

A more generous allowance must be labeled an additional grant. Narrower
eligibility, an ordinary license available only as a rental, distribution
available only through negotiation, a different royalty, or a restriction on
competition changes the license itself. Such a license cannot be presented as
this Bread License with different pricing. Adopters choose how to govern
contributions; Jig's contributor agreement is not part of Bread.

## Prepare an adoption

### 1. Check your authority

Identify the material you can license and the licenses that remain separate.
Check contributor and dependency permissions. A file named `LICENSE.md`
does not supply missing authority or revoke old licenses.

### 2. Publish the text, prices, and contacts

Keep the exact Bread text and version with the software. Complete the notice
below alongside it. Publish the direct pricing schedule and working contacts
for purchases and publisher enrollment. A monitored email channel and ordinary
records can satisfy this; a custom billing platform is not required.

### 3. Keep release records

Preserve official release identifiers and first-publication timestamps in UTC.
An accepted Update Term includes existing official releases and those first
published during that term, even if later public terms change. Obtain the
authority to cover those releases before promising it. A major version or
ordinary rename cannot take away coverage already acquired.

### 4. Give buyers records they can keep

Give buyers a durable copy of their accepted terms and order. Record the
Licensor/seller, covered Software and customer Group, exact license and dated
pricing schedule, full price and taxes, Update Term dates, payment or accepted
invoice, and renewal and cancellation choices. Email or a downloadable document
is enough.

### 5. Record publisher enrollments and customer coverage

For a publisher enrollment, preserve the parties, named offering, accepted
license version, receipt date, and reporting frequency (annual by default, or
quarterly at the publisher's choice). Keep any notice changing frequency for the
next calendar year. Apply section 6 without individual product
approval. Each time the publisher supplies included coverage, it records the
named product, covered Software releases, and the customer's coverage for
delivered copies or the hosted period. It reports aggregate receipts; no
customer list goes to the Licensor.

These duties belong to the adopter. Free users do not have to register,
contact sales, or get a certificate. Preserve grants when a seller changes;
do not make a live registry or runtime license server the evidence of permission.

### Adoption notice template

```text
Status: [Proposed, not effective / expressly adopted from stated release]
Software: [name and precise covered material or paths]
Licensor: [legal identity, notice address, and licensing capacity]
Authorized seller(s): [identity and scope, or Licensor itself]
Licensing and notices contact: [working address/channel]
Bread text: [exact version and retained local copy]
Official releases: [publication record and release identifiers]
Separate material: [dependencies/projects and where their terms are supplied]
Direct pricing: [dated schedule, currency, amounts/bands, offered Update Terms]
Purchase channel: [working route]
Publisher enrollment: [working receiving route for section 6 acceptance]
Additional grants: [none, or clearly identified expansion of rights]
```

An incomplete example does not put the license into effect. Identify specific
releases when putting an adoption into effect; do not use a broad notice that
silently covers material already licensed differently. Keep the exact accepted
notice and price versions with commercial records. No project needs permission
from Jig merely to use the proposed model.

## Dependencies and downstream notices

### Check each dependency and its cost

An application publisher should list each separately licensed component,
its version, Licensor, and how permission is obtained. For each component,
either recipients use their own applicable permission or an applicable
agreement includes coverage with the product. Do not describe all dependencies
as included when one still requires separate permission.

Two independent components each subject to 1% of the same $100 of Covered
Receipts mean $1 to each Licensor and two aggregate reporting relationships.
Five mean $5 and five reporting relationships, not one shared 1% payment. Apply
each agreement's actual receipts definition; deductions, bundles, reseller status,
and existing coverage can change the result. Five agreements mean five reports per full calendar year on the annual default,
or twenty if the publisher chooses quarterly for all five. Report and pay
within 30 days after each period ends; there is no small-balance carry-forward.
A frequency change takes effect next calendar year after notice before that
year starts, without postponing existing deadlines.

Prefer Bread for a deliberate selection of substantial products; do not
recommend it indiscriminately for every small dependency. A shared license name
removes neither accounting tasks nor other dependencies' restrictions.

### Resell a covered product

For covered resale, keep the original publisher's product coverage and the
wholesale supply's stated onward scope and quantity: what coverage can be
passed to customers, and how much. One end-user purchase does not create
unlimited customer grants. A grant already supplied for identified releases
and a stated onward scope and quantity can still be passed on after enrollment
ends. Prepaying for a future grant cannot. For example, a $40 wholesale supply
for one onward customer, resold for $100, produces $0.40 royalty for the original
publisher and no additional reseller royalty.

Suppose that reseller adds independently licensed workflows and an interface
that uses the upstream product, then sells the package under its own name.
Its customer notice identifies the upstream product and the onward coverage
supplied for it. That coverage remains sufficient: the new
interface, workflows, branding, and combined price do not trigger another royalty.
A security repair within that product or calling its runtime directly instead
of its original interface does not by itself require new coverage. The decisive
facts are the supplied onward grant and the product it covers, not the interface,
branding, or the originality of the package.

### Recognize when extra permission is needed

If the reseller instead extracts the runtime to operate separately from that
product, or supplies more customer grants than it obtained, the onward grant
does not cover those uses. To include that additional coverage, it needs an
applicable additional onward grant or its own publisher enrollment.
Alternatively, recipients can use their own applicable permissions.
For its enrolled offering with $100 of Covered Receipts, it owes $1 without
deducting component costs or upstream royalties. Permissions for independently
owned upstream material still need checking.

Extensive permitted customization or broad workloads do not alone make a
customer's purchased product an unrelated deployment. Using its covered
component independently in another product needs an applicable permission.
Decide by the product scope, not by how much code is original or what percentage
has changed.

### Distribute a fork

For a fork supplied without included product coverage, the upstream Licensor's
applicable permission covers distributed modifications under section 7. For
example, B distributes a fork of A's software, and a large company purchases
A's organization coverage for its underlying release. No second organization
license from B is required for B's distributed modifications. This also applies
to successive forks and later modifications of already-covered releases;
incorporating uncovered upstream releases still requires applicable permission.
B may charge for supplying copies, optional services, or independently licensed
additions, but not another permission fee for those covered modifications.

### Tell customers what coverage they receive

Publishers must give recipients a supply notice they can keep under section 5.
It may be included on the invoice or with the download:

```text
[Product/release] includes [covered Software/release identifiers] under
[Licensor's Bread License version and retained text]. Coverage is for this
product, not unrelated deployments or other products. [Delivered copies:
perpetual acquired-release coverage / Hosted access: stated covered dates].
Source and notices: [for distributed copies: retainable covered source and
build instructions; hosting alone does not require source disclosure].
Other components/permissions: [list, or link to supplied inventory].
```

For a free product or a paid product without included coverage, replace the
inclusion statement with a clear explanation that recipients need their own
applicable permission. Paid coverage elsewhere does not cover a free plan.

### Explain hosted coverage and charges

Permission for hosted use alone does not promise an export right, continued
service, or future maintenance. State any delivered-copy coverage and service
commitments expressly. Hosting alone does not require disclosure of private modifications.
For an enrolled paid service, charges remain Covered Receipts when priced per
result; independently selling an artifact created with the Software does not
by itself require enrollment or an output royalty.

## If the maintainer stops

Section 8 lets a Licensor close new offers immediately. Existing release rights,
accepted Update Terms and publisher agreements continue. The Licensor can hand
administration to an authorized successor, or permanently waive future royalties
and reporting for existing publisher enrollments and settle outstanding balances.
A waiver keeps the agreed coverage, including any later releases it would cover;
it does not require the maintainer to produce new releases.

For example, a publisher already enrolled for a paid product can continue under
its agreement after new enrollments close. If payment becomes impossible, it
retains its reports and amounts due until an authorized recipient can receive
them; an outage alone is neither a waiver nor a loss of permission. Existing
customers keep their rights. Someone without coverage does not acquire a new
grant merely because sales have closed; free allowances still apply normally.

## Before publishing a stable adoption

The steward must settle the exact reusable version, its text-reuse permission,
and its name policy. The proposed policy is: anyone may reproduce, translate,
adapt and distribute the text and adoption materials without a fee or membership;
only an unchanged standard bargain may be presented as that Bread License
version. Modified instruments must use a distinct name and identify their
departures; describing derivation is allowed. This is a proposed policy for
publication, not a claim of trademark registration or a grant already in effect.

Have the actual license and concrete failure cases reviewed: how grants take
effect, authority to cover future releases, continuity of customer rights,
contributor rights, mandatory software and consumer rights, taxes, and payment
arrangements. Neither agent testing nor this guide supplies that approval. Actual party
identities and operational contacts must be settled by each adopter.

During review, an SPDX record can use a locally unique `LicenseRef-` identifier
with the actual extracted text, following the [SPDX specification](https://spdx.github.io/spdx-spec/v2.3/other-licensing-information-detected/).
Include the draft identifier and adoption facts; do not imply an SPDX-listed
license, OSI approval, or legal certification. A stable identifier is a later
publication decision.
