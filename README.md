# PSD2-testing-book
Validation of the SCA requirements for web, api and mobile applications

>[Testing book](testing-book.md)

# Rationale

The *Article 97 Authentication* of the [DIRECTIVE (EU) 2015/2366](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=celex%3A32015L2366) establishes that:

1. Member States shall ensure that a **payment service provider** applies strong customer authentication where the payer:

(a) accesses its payment account online;

(b) initiates an electronic payment transaction;

(c) carries out any action through a remote channel which may imply a risk of payment fraud or other abuses.

2. With regard to the initiation of electronic payment transactions as referred to in point (b) of paragraph 1, Member States shall ensure that, for electronic remote payment transactions, **payment service providers** apply strong customer authentication that includes elements which dynamically link the transaction to a specific amount and a specific payee.

3. With regard to paragraph 1, Member States shall ensure that **payment service providers** have in place adequate security measures to protect the confidentiality and integrity of payment service users’ personalised security credentials.

4. Paragraphs 2 and 3 shall also apply where payments are initiated through a **payment initiation service provider**. Paragraphs 1 and 3 shall also apply when the information is requested through an **account information service provider**.

5. Member States shall ensure that the **account servicing payment service provider** allows the payment initiation service provider and the account information service provider to rely on the authentication procedures provided by the account servicing payment service provider to the payment service user in accordance with paragraphs 1 and 3 and, where the payment initiation service provider is involved, in accordance with paragraphs 1, 2 and 3.

where

- **‘payment service’** means any business activity set out in Annex I; (Title 1, art. 4, item 3 of the [DIRECTIVE (EU) 2015/2366](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=celex%3A32015L2366))
>1. Services enabling cash to be placed on a payment account as well as all the operations required for operating a payment account.
>  
>2. Services enabling cash withdrawals from a payment account as well as all the operations required for operating a payment account.
>
>3. Execution of payment transactions, including transfers of funds on a payment account with the user’s payment service provider or with another payment service provider:
>    - (a) execution of direct debits, including one-off direct debits;
>    - (b) execution of payment transactions through a payment card or a similar device;
>    - (c) execution of credit transfers, including standing orders.
>
>4. Execution of payment transactions where the funds are covered by a credit line for a payment service user:
>    - (a) execution of direct debits, including one-off direct debits;
>    - (b) execution of payment transactions through a payment card or a similar device;
>    - (c) execution of credit transfers, including standing orders.
>
>5. Issuing of payment instruments and/or acquiring of payment transactions.
>
>6. Money remittance.
>
>7. Payment initiation services.
>
>8. Account information services.   

- **‘payment service provider’** means a body referred to in Article 1(1):
>  - credit institutions
>  - electronic money institutions
>  - post office giro institutions
>  - payment institutions
>  - the ECB and national central banks
>  -  or a natural or legal person benefiting from an exemption pursuant to Article 32 or 33; (Title 1, art. 4, item 11 of the [DIRECTIVE (EU) 2015/2366](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=celex%3A32015L2366))


The *Article 97 Authentication* of the [DIRECTIVE (EU) 2015/2366](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=celex%3A32015L2366) establishes that:

1. EBA shall, in close cooperation with the ECB and after consulting all relevant stakeholders, including those in the payment services market, reflecting all interests involved, develop draft regulatory technical standards addressed to payment service providers as set out in Article 1(1) of this Directive in accordance with Article 10 of Regulation (EU) No 1093/2010 specifying: [..]

The regulatory technical standards have been developed and are published under the [COMMISSION DELEGATED REGULATION (EU) 2018/389](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=celex%3A32018R0389) *of 27 November 2017 supplementing Directive (EU) 2015/2366 of the European Parliament and of the Council with regard to regulatory technical standards for strong customer authentication and common and secure open standards of communication.*

>The regulation EU 2018/389 apply from 14 March 2019. It is up to the payment service providers ensure compliance with the technical standards required by the referred regulation.

## Penalties:

Article *103 Penalties* of the [COMMISSION DELEGATED REGULATION (EU) 2018/389](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=celex%3A32018R0389) states that:

1. Member States shall lay down rules on penalties applicable to infringements of the national law transposing this Directive and shall take all necessary measures to ensure that they are implemented. Such penalties shall be effective, proportionate and dissuasive.
2. Member States shall allow their competent authorities to disclose to the public any administrative penalty that is imposed for infringement of the measures adopted in the transposition of this Directive, unless such disclosure would seriously jeopardise the financial markets or cause disproportionate damage to the parties involved.

## Why a testing book for SCA requirements for web, api and mobile applications?

Enabling guidance through that legislation enables independent testers or testing companies without strong regulatory skills to develop testing scenarios that fulfill the security and quality requirements of banking services offered via internet. By compile and providing all the testable requirements in a single list it reduces the operational cost involved in "draining" the legislation to extract testable and actionable requirements from it and provides the necessary substract to ensure compliance with PSD2 requirements.

Many banking services are offered through web, apis, mobile or a combination of them. Many of the requirements specified at [COMMISSION DELEGATED REGULATION (EU) 2018/389](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=celex%3A32018R0389) can be technically validated against their implementation, which certainly increases the confidence of banking institutions when providing services via one or many of those channels.

## References:
- [Directive (EU) 2015/2366](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=celex%3A32015L2366)
- [COMMISSION DELEGATED REGULATION (EU) 2018/389](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=celex%3A32018R0389)
- [Regulation (EU) No 575/2013](https://eur-lex.europa.eu/legal-content/en/TXT/?uri=celex:32013R0575)
- [Directive 2009/110/EC](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=celex%3A32009L0110)
- [EBA Single Rulebook](https://www.eba.europa.eu/regulation-and-policy/single-rulebook)
