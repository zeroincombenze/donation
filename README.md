[![Build Status](https://travis-ci.org/OCA/donation.svg?branch=10.0)](https://travis-ci.org/OCA/donation)
[![Coverage Status](https://coveralls.io/repos/OCA/donation/badge.png?branch=10.0)](https://coveralls.io/r/OCA/donation?branch=10.0)

# Donation

This project develops Odoo modules for advanced management of donations. With the modules available in this project, you can manage:
* simple donations via checks, cash, credit card, online payment and wire transfers.
* recurring donations via direct debit and credit transfers.
* tax receipts that are sent back to donors, either one-time or annual tax receipts.
* edition of the thank you letter.

The donations modules are fully integrated with the accounting and payment modules of Odoo. When you validate a donation in Odoo, the corresponding accounting entries are automatically generated. Donations via credit transfer are identified and generated from the bank statements of Odoo. If you also install the OCA module for [SEPA direct debit](https://github.com/OCA/bank-payment/tree/10.0/account_banking_sepa_direct_debit), you can organise your recurring donations via direct debit and easily generate the SEPA XML file for the bank.

These modules have been developped by the
[Barroux Abbey](http://www.barroux.org/), a Benedictine Abbey located near the
[Mont Ventoux](http://en.wikipedia.org/wiki/Mont_Ventoux) in France,
who decided to publish these modules so that they can benefit to
associations, NGOs and other religious organisations. These modules are
fully mature: they are used in production at the Barroux Abbey since
January 1st 2015.

The main developpers of the project are:
* Brother Bernard (Barroux Abbey)
* Brother Irénée (Barroux Abbey)
* Alexis de Lattre (Akretion)

Please refer to the README of each module to have more information about
how to configure and use the modules.

[//]: # (addons)

Available addons
----------------
addon | version | maintainers | summary
--- | --- | --- | ---
[donation](donation/) | 10.0.1.0.0 |  | Manage donations
[donation_bank_statement](donation_bank_statement/) | 10.0.1.0.0 |  | Creates donation from unreconciled bank statement lines
[donation_base](donation_base/) | 10.0.1.0.0 |  | Base module for donations
[donation_direct_debit](donation_direct_debit/) | 10.0.1.0.0 |  | Auto-generate direct debit order on donation validation
[donation_recurring](donation_recurring/) | 10.0.1.0.0 |  | Manage recurring donations
[donation_sale](donation_sale/) | 10.0.1.0.0 |  | Manage donations in sale orders
[donation_thanks](donation_thanks/) | 10.0.1.0.0 |  | Create thanks letter for a donation
[product_analytic_donation](product_analytic_donation/) | 10.0.1.0.0 |  | Glue module between donation and product_analytic

[//]: # (end addons)
