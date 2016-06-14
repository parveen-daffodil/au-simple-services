# Simple Services Agreement

`Purpose` If you provide services to people as a contractor (software development, graphic design - stuff like that), the _Simple Services Agreement_:
- gets you paid;
- limits what you can get sued for; and
- makes clear what you agree to do for the customer.

This agreement is on [Github in Markdown](https://github.com/CodePact/au-simple-services/blob/master/au-simple-services.md). If you’re logged in to Github, [click here to fork this document](https://github.com/CodePact/au-simple-services/fork). This is an **open source** document – edits are welcome!

`Party 1 Name` Contractor

`Party 2 Name` Customer

`Jurisdiction` Australia

## Agreement length

https://github.com/CodePact/au-components/blob/master/agreement_duration.md

## Calculation of payment

https://github.com/CodePact/au-components/blob/master/payment_calculation.md

## Payment method

https://github.com/CodePact/au-components/blob/master/payment_method.md

## Timing for completion

When the contractor is working on a project scope for a fixed amount of money, the parties need to agree whether or not the timeframe for completion is a **deadline** or an **estimate**.

### Contractor only estimates when it will finish the Work Scope.

Contractor estimates that it will complete the Services by approximately {{estimate timeframe}}. The parties agree that the timeframe in this clause is an estimate only, and is not binding on Contractor.

### Contractor promises to finish the Work Scope by a specific date.

Contractor will achieve completion of the Services {{deadline}}.

## Out of scope work

When you’re providing services to complete a project scope, there are often changes to the scope. There needs to be a system for calculating how the contractor will be paid for extra work caused by changes.

### Customer will pay Contractor a pre-agreed hourly rate for any variations that increase the Work Scope.

- If Contractor provides Services not covered by the Work Scope and the Services outside the Work Scope increase the amount of work for the Contractor to complete the Work Scope, Customer will pay Contractor a rate of {{out scope rate}} for the extra hours worked.
- Contractor may invoice Customer for extra hours worked at its discretion, Customer will pay within {{payment terms}} of receiving the invoice.

## Confidentiality

https://github.com/CodePact/au-components/blob/master/confidentiality.md

## Intellectual property

https://github.com/CodePact/au-components/blob/master/intellectual_property.md

## Amount a party can get sued for 

https://github.com/CodePact/au-components/blob/master/limitation.md

## Termination of agreement

This topic makes clear under what conditions the parties can terminate the agreement prematurely.

### If a party breaks the contract, the other party can terminate the contract.

- Either party may terminate the Agreement immediately if:
	- a party notifies the other party of an Agreement breach; and
	- 10 days after the breach notification, the Agreement breach is not remedied.
- Either party may also immediately terminate the Agreement if the other party becomes insolvent.

### Either party can end the agreement whenever they like with a certain amount of warning.

Either party may terminate the Agreement {{termination process}}.

## Other (necessary) bureaucracy

https://github.com/CodePact/au-components/blob/master/end_agreement.md

## Definitions

### Agreement
means the agreement arising between the parties in accordance with this document and the other documents referred to by this document.

### Background IP
means the intellectual property rights owned by Contractor prior to the creation of the Agreement.

### Communication, Communications
means any contractual communication in connection with the Agreement.

### Confidential Information
means any information disclosed by the Customer to the Contractor in connection with the Services, not including information that:

- is known to the Contractor at the time of disclosure;
- is or becomes publicly accessible; or
- is provided to the Contractor by a third party,

unconnected with a breach of the Agreement by either party.

### Contributed IP
means the intellectual property rights owned by Customer prior to the creation of the Agreement.

### GST Law
means the _A New Tax System (Goods and Services Tax) Act_ 1999 (Cth).

### New IP
means the intellectual property rights created under the Agreement.

### Service, Services
means {{services description}}.

### Services IP
means the intellectual property rights in the Services rendered by Contractor to Customer.

### Work Scope
means the document {{work scope document}} that sets out the scope of work to be delivered by Contractor to Customer.

## Variables

#### billing cycle period

month

`Guidance` Fill in this variable with a time period for the billing cycle. It’s great to get paid weekly, but you have to issue an invoice before you get paid. The billing cycle period is a balance between keeping your cash flow regular and the administrative overhead of issuing the invoices required to get paid.

#### completion amount

50% of the total amount payable for the Services

`Guidance` The completion amount is the money paid after the completion of the services. It is usually defined as a percentage amount of the overall cost of the development services under the agreement.

#### deadline

22 March 2016

`Guidance` Give yourself enough time! Remember that the date or timeframe that you enter in here must be honoured or you may have to reduce the price of the services to the customer.

#### deposit amount

50% of the total amount payable for the Services [OR] $ DOLLAR_AMOUNT

`Guidance` The deposit is a non-refundable upfront payment for the services. It is usually defined as a percentage amount of the overall cost of the development services under the agreement. You could also use an amount, though.

#### estimate timeframe

3 months after the parties enter the Agreement

#### fees table

| Work Description | Amount
|----------------------|--------
| Visual design for the app called "Example App" | $ 3,000
| DESCRIBE SERVICE | $ AMOUNT

`Guidance` Fill in the [markdown table](https://help.github.com/articles/github-flavored-markdown/) with the cost components of the services. In the left column, describe the service, and in the right column, describe the price as a dollar value.

#### governing law state

New South Wales

`Guidance` This is the state that you will go to court in if there’s legal action under this document. It’s usually better to have a "home court" advantage. If your business is in New South Wales, make the forum the New South Wales courts.

#### licence characteristics

for [period of time] that is non-transferrable, unsublicensable, for the territory of [country name]

`Guidance` What you type here determines the kind of licence created. The table below works as follows:
- "Words" are the relevant words in the default guidance text;
- "Effect of Inclusion" means what happens to the licence if you leave the words in; and
- "Effect of Deletion" means what happens to the licence if you delete the words.

| Words | Effect of Inclusion | Effect of Deletion
|----------------------|--------|--------
| "for [period of time]" | licence will be granted for the length of time stipulated | licence lasts forever
| "non-transferrable" | licence **cannot be transferred** to any third party | licence **can be transferred** to any third party
| "unsublicensable" | licence **cannot be licenced** to any third party | licence **can be licenced** to any third party
| "for the territory of [country name]" | fill in the country name, you’ll be limiting the licence to the country that you type in | licence is **global**
#### license purpose

any purpose whatsoever

`Guidance` This variable sets out the boundaries for the use of the intellectual property. The default value here of "any purpose whatsoever" is very expansive: it allows the recipient of the license to use the code in whatever way they want to, which the ownership remains with the license giver.

#### limitation amount

the amount paid to Contractor by the Customer in exchange for the Services [OR] $AMOUNT

`Guidance` Describe the amount of money that the customer can sue the contractor for. The example text allows the customer to get a full refund, since the Contractor can sue for the amount paid for the services by the customer. You can describe the amount or put a specific dollar figure on it.

#### milestones

| Milestone | Payment
|----------------------|--------
| Completion of app functionality to post to Facebook (example) | $500
| DESCRIBE MILESTONE | PAYMENT

`Guidance` This table variable is where you define the milestones for payment. The "Milestone" column is where the parties describe the services milestone that triggers the ability of the contractor to invoice for the amount in the "Payment" column. It's important to provide as much detail as possible about each milestone. An example might be, "Completion of the wireframe diagrams for the home page, profile page and news feed page."

#### out scope rate

$[*] per hour

#### payment period

14 days

`Guidance` Fill this variable in with the amount of time between the customer receiving the invoice and the invoice's due date for payment.

#### payment terms

14 days

`Guidance` This is the amount of time between the customer receiving the invoice and the invoice's due date for payment.

#### rate of payment

$ NUMBER per hour [OR] $ NUMBER per day

`Guidance` This variable can be filled in with: (1) the hourly rate of the contractor; or (2) the daily rate of the contractor.

#### risks to exclude

[PEOPLE AND PROPERTY]

- any death or injury;
- any property damage;

[DIGITAL INDUSTRIES]

- failure of any software, hardware or network components provided by a third party;
- software or hardware that's inaccessible for any reason;
- faulty or lost data associated with the Services;
- digital security issues like software vulnerabilities and malware;
- software in a testing phase like (or analogous to) beta and alpha software;

[CONSULTING]

- reliance on advice communicated by Contractor in whatever form;
- failure to provide correct information or opinions;
- faulty technical advice or data;

[CONSTRUCTION]

- failure of any third party equipment or materials;
- loss connected with access or access problems to the site of work;
- failure to use safety procedures or methods;
- loss during the process of delivery;
- the use, or breakdown of equipment used for the services;

[AGREEMENT RISKS]

- any act or omission connected with the Agreement;
- breaches of the Agreement;
- the termination of the Agreement; or
- any delay in the provision of the Services;

`Guidance` It’s very important to set out the risks that are most likely to cause problems (and get the contractor sued). Don’t rely on the lists in the default text – think of the biggest risks around the services you provide!

#### services description

freelance software development and design services in relation to "[App Name]"

`Guidance` Describe the services provided under the agreement! You need to be specific enough to make clear what the agreement deals with.

#### term duration

for NUMBER days [OR] NUMBER weeks [OR] NUMBER months after the parties enter the Agreement

`Guidance` Fill in the period of time that the agreement will exist between the contractor and the customer. The contractor will provide the services for this period of time, and the customer will need to pay for the services for this period of time.

#### termination process

with 10 days of written notice to the other party

`Guidance` This is how a party can terminate the agreement. The default text sets out a system where you need to warn the other party with a written notification ten days before you terminate the agreement.

#### total amount

$ AMOUNT (including $[*] GST)

`Guidance` Fill in this variable with the total amount that the customer will pay the contractor for the services. It should be an all-inclusive amount because this is the _total_ amount. It’s probably a good idea to set out the amount of GST too.

#### work scope document

the document provided by Contractor to Customer entitled "Scope of Work", dated [insert date]

`Guidance` Fill this in with a description of the "Scope of Work" document that sets out the specifications of work to be completed.
