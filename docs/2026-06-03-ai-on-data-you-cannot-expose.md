# You can use AI on data you're not allowed to expose

`2026 June 3`

The most common reason a business says no to AI is that the useful data is the data it cannot send anywhere: patient records, client files, payroll, anything covered by a confidentiality clause. The assumption is that using AI means handing that data to a third party. It no longer has to.

There are now several distinct ways to keep the data where it belongs. [Confidential computing](disclaimer.md) runs inference inside a hardware enclave the cloud provider itself cannot read. [Federated learning](disclaimer.md) trains a model across client premises without the data ever leaving them. [Redaction and anonymisation](disclaimer.md) strips the personal detail before a single token reaches a model. And for the most sensitive cases, [running a capable model on local hardware](disclaimer.md) means nothing crosses the network at all.

This matters because the privacy objection is usually treated as a reason to wait, when it is really a design choice that was made by default. The question is not whether AI is safe for sensitive data in the abstract. It is which of these arrangements fits a particular business, and whether anyone has actually been asked to set one up.
