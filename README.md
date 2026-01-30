# SAML Response Diff

SAML Response Diff is a lightweight, client-side web application designed to help developers and identity engineers compare and analyze SAML Assertions (responses sent to SP). It provides a side-by-side comparison of key fields and an interactive XML explorer.

[https://trustbuilder.github.io/saml-response-diff](https://trustbuilder.github.io/saml-response-diff/)

## 🚀 Key Features

- Field-by-Field Comparison: Automatically extracts and compares critical SAML elements like Issuer, Subject (NameID), Audience, and Attributes.
- Namespace Agnostic: Works seamlessly with different SAML prefixes (saml:, saml2:, or none) and various Identity Provider formats (Okta, Azure AD, Ping, etc.).
- Interactive XML View: A syntax-highlighted XML explorer with collapsible branches to easily navigate deep structures.
- Customizable Labels: Rename your assertions (e.g., "Production" vs "Staging") for clearer reports.
- Privacy First: 100% client-side processing. Your sensitive SAML data never leaves your browser and is never sent to a server.
- Portable: A single HTML file with no build step required.

## 🛠️ How to Use

1. Open the App: Open [https://trustbuilder.github.io/saml-response-diff](https://trustbuilder.github.io/saml-response-diff/) in any modern web browser.

2. Input Data:
   - Paste your first SAML XML Response into the left box.
   - Paste your second SAML XML Response into the right box.
   - Optionaly change the default names "SAML Assertion A" and "SAML Assertion B".

3. Compare: Click the "Compare" button.

4. Analyze:
   - Use "Field View" to see extracted data and highlighted differences.
   - Use "XML View" to explore the raw structures side-by-side.
