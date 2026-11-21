BLACKGRID INNOVATIONS

BlackGrid Cannabis OS

Product Type: Cannabis Business Operating System
Initial Market: Michigan, USA
Expansion Goal: Nationwide
Company: BlackGrid Innovations
Project Status: Architecture and Planning

⸻

1. Vision

BlackGrid Cannabis OS is an integrated technology platform designed to help cannabis dispensaries operate more efficiently, reduce operating costs, increase profitability, improve inventory management, and make better business decisions.

BlackGrid is designed to work alongside existing point-of-sale (POS) systems rather than replace them.

Our goal is to give cannabis business owners one connected platform to understand and manage their operations.

2. Core Mission

BlackGrid aims to:

* Reduce repetitive employee tasks through automation.
* Identify lost revenue and unnecessary expenses.
* Improve inventory management and purchasing decisions.
* Analyze sales trends and product performance.
* Help dispensaries understand which promotions generate actual profit.
* Compare vendor pricing and identify purchasing opportunities.
* Support authorized compliance monitoring and recordkeeping.
* Improve the customer shopping and pickup experience.
* Help owners make informed decisions using their business data.

3. Target Customers

BlackGrid will initially serve:

* Independent cannabis dispensaries.
* Multi-location cannabis operators.
* Cannabis retail business owners and managers.

The platform will begin in Michigan, with an architecture designed to support additional states and their different regulatory requirements.

4. Product Philosophy

BlackGrid is not intended to replace existing POS platforms or state-mandated tracking systems.

It will connect to authorized systems and bring operational intelligence, automation, and business management tools together in one platform.

Every feature should solve a real business problem, save time, reduce costs, or improve profitability.

5. Development Principles

* Build securely from the beginning.
* Support multiple businesses and locations.
* Protect each customer’s business data.
* Use authorized integrations.
* Maintain accurate records and audit trails.
* Design modules that can grow independently.
* Build for long-term nationwide expansion.
6. BlackGrid Operating Modules

BlackGrid Cannabis OS will consist of connected modules that work together to improve dispensary operations.

6.1 BlackGrid Intelligence

The business intelligence center.

* Daily, weekly, and monthly sales reporting.
* Best-selling and slowest-selling products.
* Product, brand, and category performance.
* Revenue and profit analysis.
* Sales trend identification.
* Demand forecasting.
* Multi-location performance comparisons.

6.2 BlackGrid Inventory Guardian

The inventory management and monitoring center.

* Real-time inventory visibility when supported by connected systems.
* Low-stock alerts.
* Slow-moving and aging inventory detection.
* Inventory discrepancy monitoring.
* Overstock identification.
* Product expiration and aging alerts when data is available.
* Stockout risk forecasting.

6.3 BlackGrid Profit Leak Detector

The financial intelligence center.

* Identify products with declining margins.
* Detect excessive discounting.
* Identify unnecessary purchasing costs.
* Analyze product profitability.
* Compare revenue, discounts, returns, and cost of goods.
* Highlight potential savings opportunities.

6.4 BlackGrid Promotions

The promotion and deal intelligence center.

* Track vendor-provided deals.
* Track dispensary promotions.
* Compare promotion performance.
* Calculate discount costs.
* Identify promotions that increase profitable sales.
* Identify promotions that reduce profitability.
* Recommend better promotional opportunities.

6.5 BlackGrid Procurement

The vendor and purchasing center.

* Organize vendor information.
* Compare supplier pricing.
* Track vendor offers and deals.
* Recommend purchasing opportunities.
* Monitor purchasing history.
* Help prevent unnecessary inventory spending.
* Prepare purchase order recommendations for approval.

6.6 BlackGrid Compliance Guardian

The compliance monitoring center.

* Monitor authorized inventory and sales data.
* Identify potential discrepancies.
* Generate operational alerts.
* Maintain audit history.
* Track integration and synchronization status.
* Support jurisdiction-specific compliance workflows.

BlackGrid will not replace state-mandated tracking systems or the licensee’s legal compliance responsibilities.

6.7 BlackGrid Customer Experience

The customer shopping and service center.

* Digital product catalog.
* Customer deal discovery.
* Digital check-in.
* Order preparation workflow.
* Customer self-service tools.
* Reduce repetitive employee tasks.
* Help employees focus on customers who need personal assistance.

6.8 BlackGrid Smart Automation

The future hardware and automation division.

* Self-service kiosks.
* Smart pickup lockers.
* Customer identity verification workflows.
* Secure pickup authorization.
* Automated pickup notifications.
* Integration with approved dispensary systems.

Hardware development will happen after the core software is proven.

⸻

7. Connected Business Intelligence

All modules should share authorized business information so BlackGrid can identify opportunities across the entire operation.

Examples:

* Inventory data combined with sales trends can identify products at risk of selling out.
* Vendor pricing combined with product margins can identify better purchasing opportunities.
* Promotion data combined with sales and costs can show whether a deal actually increased profit.
* Customer shopping trends can help improve product availability and merchandising while protecting customer privacy.

The objective is to give owners one connected view of their business rather than requiring them to use disconnected reports and spreadsheets.

8. Product Development Priority

Initial development priorities:

1. BlackGrid Intelligence.
2. BlackGrid Inventory Guardian.
3. BlackGrid Profit Leak Detector.
4. BlackGrid Promotions.
5. BlackGrid Procurement.
6. BlackGrid Compliance Guardian.
7. BlackGrid Customer Experience.

Smart kiosks and pickup lockers will be developed in a later phase.

9. POS and External System Integrations

BlackGrid Cannabis OS will support a flexible integration architecture.

9.1 Direct POS Integrations

BlackGrid will connect directly to POS providers through authorized APIs and approved developer integrations.

The system should support:

* Sales transactions.
* Product catalogs.
* Inventory information.
* Product pricing.
* Discounts and promotions.
* Returns and adjustments.
* Location information.

9.2 Third-Party Integration Providers

When direct integration is unavailable or impractical, BlackGrid may use authorized third-party integration providers.

9.3 Integration Architecture

All integrations must use a standardized internal data structure.

Each external provider will have its own integration adapter so that adding or replacing a provider does not require rebuilding the entire platform.

9.4 Data Synchronization

The platform must support:

* Scheduled and incremental synchronization.
* Duplicate transaction prevention.
* Pagination.
* Retry handling.
* Synchronization logs.
* Data freshness indicators.
* Error notifications.
* Source identification.

9.5 Security and Authorization

* Use approved API access.
* Securely store integration credentials.
* Never expose API secrets in the frontend.
* Respect provider permissions and rate limits.
* Maintain an audit trail.
* Support location-specific access permissions.

9.6 Future Expansion

The integration architecture must allow BlackGrid to support additional POS providers, third-party services, and jurisdiction-specific regulatory systems as the company expands nationwide.

10. Technical Architecture

BlackGrid Cannabis OS will use a modular monolith architecture for its initial development.

The architecture must be affordable to develop, secure, maintainable, and capable of supporting nationwide expansion.

10.1 Frontend

Initial technologies:

* Next.js.
* React.
* TypeScript.
* Tailwind CSS.
* shadcn/ui.

The frontend will provide the dashboards, reports, inventory screens, business tools, and customer-facing experiences.

10.2 Backend

The initial backend will use Next.js server-side functionality.

It will manage:

* Business logic.
* POS integrations.
* Data processing.
* Business reporting.
* Automation workflows.
* User permissions.
* API communication.

Sensitive operations must never depend on frontend-only security.

10.3 Database

Supabase PostgreSQL will serve as the initial database platform.

The database must support:

* Multiple organizations.
* Multiple dispensary locations.
* Users and memberships.
* Products and inventory.
* Sales and transactions.
* Vendors and purchasing.
* Promotions and discounts.
* Compliance monitoring.
* Integration records.
* Audit history.

Financial values must use precise decimal database types rather than floating-point calculations.

10.4 Authentication and Security

Supabase Auth will provide user authentication.

Row-Level Security (RLS) will enforce organization and location-based data access.

Security requirements:

* Strict separation between customer organizations.
* Role-based permissions.
* Secure credential storage.
* Encrypted communication.
* Audit logging.
* Minimal collection of customer information.
* Secure handling of integration credentials.

10.5 Modular Application Design

Each BlackGrid operating module must have clearly separated responsibilities while sharing authorized business data.

The initial application will remain one deployable system with organized internal modules.

10.6 Scalability

The architecture must support:

* Independent dispensaries.
* Multi-location operators.
* Multiple states.
* Different state-specific regulatory requirements.
* Additional POS integrations.
* Future kiosk and locker hardware.

State-specific rules must be configurable rather than hardcoded throughout the application.

10.7 Source Code Ownership

GitHub will serve as the primary source-code repository.

The project must remain portable so BlackGrid is not permanently dependent on a single visual development platform.

All production credentials and secrets must remain outside the public source code.

11. Database Architecture and Data Organization

BlackGrid will use a relational PostgreSQL database.

The database must support multiple organizations, multiple dispensary locations, secure data separation, and connected business intelligence.

11.1 Organization Management

Organizations represent individual cannabis businesses.

Each organization may have multiple locations and users.

11.2 User Management

Store:

* User accounts.
* Organization memberships.
* Location permissions.
* Roles and access permissions.

Initial roles:

* Owner.
* Administrator.
* Manager.
* Employee.
* Read-only analyst.

11.3 Location Management

Each dispensary location must belong to an organization.

Location records will include:

* Location name.
* Address.
* State and jurisdiction.
* POS connection.
* Operating status.

11.4 Product Management

Product records must support:

* Product name.
* SKU.
* Brand.
* Category.
* Package identifier when applicable.
* External POS product identifier.
* Cost information.
* Retail price.
* Active status.

Product SKUs and regulated package identifiers must remain separate fields.

11.5 Sales Management

Sales records must support:

* Transaction identifier.
* Organization.
* Location.
* Transaction date.
* Product details.
* Quantity.
* Gross sales.
* Discounts.
* Returns.
* Net sales.
* Taxes.
* Cost of goods when available.
* Source system.

Tax collected must not be treated as ordinary business revenue.

11.6 Inventory Management

Inventory records must support:

* Product.
* Location.
* Quantity on hand.
* Inventory movement.
* Package information.
* Inventory adjustments.
* Stock levels.
* Last synchronization time.

11.7 Vendor and Purchasing Management

Vendor records must support:

* Vendor information.
* Products offered.
* Pricing.
* Discounts and deals.
* Purchase history.
* Purchase orders.
* Order recommendations.
* Approval status.

11.8 Promotion Management

Promotion records must support:

* Promotion name.
* Vendor or dispensary source.
* Eligible products.
* Discount structure.
* Start and end dates.
* Redemption history.
* Discount costs.
* Sales performance.
* Profit impact.

11.9 Compliance and Audit Management

Store:

* Authorized compliance monitoring events.
* Potential discrepancy alerts.
* User actions.
* Record changes.
* Integration synchronization history.
* Audit timestamps.

11.10 Integration Management

Store:

* POS provider.
* Integration provider.
* Organization and location association.
* Connection status.
* Synchronization history.
* External record identifiers.
* Error history.

Credentials and API secrets must be stored securely outside ordinary application tables.

11.11 Database Security Requirements

* Every organization-owned record must have an organization association.
* Location-specific records must also identify their location.
* Row-Level Security must prevent unauthorized cross-organization access.
* Database relationships must enforce data integrity.
* Financial calculations must use precise numeric values.
* Duplicate external transactions must be prevented.
* Important changes must be auditable.
* Test data must be separated from production data.

11.12 Business Intelligence Data

BlackGrid will use authorized sales, product, inventory, vendor, and promotion records to calculate business insights.

If required information is missing, BlackGrid must identify the result as unavailable or estimated rather than inventing a financial value.

12. Financial Intelligence and Profit Analysis

BlackGrid must provide accurate financial intelligence that helps cannabis businesses understand revenue, costs, profitability, and potential savings.

12.1 Revenue Analysis

BlackGrid will calculate and report:

* Gross sales.
* Discounts.
* Returns and refunds.
* Net sales.
* Taxes collected.
* Sales trends.
* Revenue by product.
* Revenue by category.
* Revenue by brand.
* Revenue by location.

Taxes collected must be reported separately from business revenue.

12.2 Product Profitability

BlackGrid will analyze:

* Product cost.
* Retail selling price.
* Units sold.
* Discount impact.
* Cost of goods sold.
* Gross profit.
* Gross profit margin.

Gross Profit = Net Sales - Cost of Goods Sold.

Gross Margin Percentage = (Gross Profit / Net Sales) × 100.

If product cost information is missing or outdated, profitability must be labeled unavailable or estimated.

12.3 Profit Leak Detection

BlackGrid will identify potential financial problems, including:

* Excessive discounting.
* Products with declining margins.
* Products that sell below target profitability.
* Unnecessary purchasing costs.
* Overstock and aging inventory.
* Unprofitable promotions.
* Vendor price increases.
* Unexpected sales or inventory discrepancies.

Each alert should explain the reason and provide supporting data.

12.4 Promotion Profitability

BlackGrid must evaluate whether promotions create actual financial value.

Promotion analysis will include:

* Total discounted sales.
* Discount expense.
* Units sold.
* Product costs.
* Gross profit.
* Comparison with a reasonable baseline.
* Estimated incremental sales.
* Estimated incremental profit.

A promotion should not be considered successful simply because it increases sales volume.

12.5 Vendor Savings Intelligence

BlackGrid will compare authorized vendor pricing and offers.

The system should identify:

* Lower available prices for comparable products.
* Vendor discounts.
* Volume pricing.
* Purchasing opportunities.
* Changes in supplier pricing.
* Potential purchasing savings.

Recommendations must account for product quality, availability, minimum order requirements, and other relevant conditions when available.

12.6 Inventory Financial Intelligence

BlackGrid will connect inventory and sales data to identify:

* Capital tied up in slow-moving inventory.
* Products at risk of becoming overstocked.
* Products likely to sell out.
* Reorder opportunities.
* Potential losses from aging inventory.

12.7 Business Savings Reports

BlackGrid will provide reports showing:

* Identified savings opportunities.
* Estimated financial impact.
* Actual savings when verified.
* Recommendations completed.
* Recommendations declined.
* Results after implementation.

Estimated savings must never be presented as guaranteed savings.

12.8 Financial Data Accuracy

* Use precise decimal calculations.
* Identify missing data.
* Distinguish actual results from estimates.
* Track the source of financial information.
* Avoid double-counting discounts or returns.
* Maintain calculation consistency across reports.
* Allow authorized users to inspect the underlying numbers.

The objective is to give owners trustworthy financial information they can use to make better decisions.

13. Two-Sided Vendor and Promotion Intelligence

BlackGrid will provide business intelligence for both cannabis retailers and authorized suppliers.

The goal is to improve purchasing decisions, promotional effectiveness, product visibility, and business relationships.

13.1 Dispensary Intelligence

Dispensaries will be able to:

* View available vendor offers.
* Compare authorized supplier pricing.
* Identify purchasing discounts.
* Evaluate wholesale deals.
* Track promotion performance.
* Identify profitable products.
* Discover opportunities to reduce purchasing costs.

13.2 Supplier Intelligence

Authorized suppliers may eventually receive a separate supplier portal.

Supplier features may include:

* Product performance reporting.
* Authorized promotion tracking.
* Offer management.
* Campaign performance.
* Aggregated sales trends.
* Product demand insights.
* Promotion effectiveness reports.

13.3 Deal Management

BlackGrid will support:

* Vendor-provided deals.
* Dispensary-created promotions.
* Product discounts.
* Volume discounts.
* Limited-time offers.
* Promotion eligibility.
* Offer expiration tracking.
* Deal comparison.

13.4 Two-Sided Savings Analysis

BlackGrid will analyze the financial impact of deals on both sides.

For dispensaries:

* Purchasing savings.
* Product margins.
* Promotion costs.
* Inventory efficiency.
* Incremental profit.

For suppliers:

* Campaign performance.
* Product movement.
* Promotion effectiveness.
* Authorized aggregated demand trends.

13.5 Data Privacy and Permissions

* Suppliers must never access unauthorized dispensary financial records.
* Dispensaries must never access another business’s private purchasing information.
* Supplier reporting must be permission-based.
* Aggregated reporting must protect business confidentiality.
* Customer-identifying information must not be exposed to suppliers.
* Every organization must control its data-sharing permissions.

13.6 Future Business Network

BlackGrid may eventually develop a business network connecting dispensaries and suppliers through authorized offers, product information, and purchasing opportunities.

The network must create measurable value without compromising customer privacy or business confidentiality.

14. Business Automation and Employee Efficiency

BlackGrid will reduce repetitive administrative and operational work through intelligent automation.

The objective is to allow dispensary employees to focus on customer service, product education, and tasks requiring human judgment.

14.1 Inventory Automation

* Generate low-stock alerts.
* Identify potential stockouts.
* Recommend reorder quantities.
* Identify slow-moving inventory.
* Prepare inventory review reports.

14.2 Purchasing Automation

* Compare vendor pricing.
* Identify available deals.
* Prepare suggested purchase orders.
* Notify managers when approvals are required.
* Track order status.

Purchasing recommendations must remain subject to authorized human approval.

14.3 Reporting Automation

* Generate daily sales reports.
* Generate weekly performance reports.
* Summarize inventory changes.
* Identify unusual business activity.
* Deliver authorized management notifications.

14.4 Customer Service Automation

* Digital customer check-in.
* Product catalog browsing.
* Deal discovery.
* Order preparation workflows.
* Pickup notifications.
* Self-service kiosk integration.

All customer identity verification, purchasing, and pickup workflows must comply with applicable laws and approved system requirements.

14.5 Employee Task Management

BlackGrid should help employees understand:

* What needs attention.
* Which products need restocking.
* Which orders need preparation.
* Which alerts require review.
* Which tasks are overdue.

14.6 Human Oversight

Automation must not independently perform regulated or financially significant actions without appropriate authorization.

The platform must:

* Require approval for designated actions.
* Record automated recommendations.
* Log user approvals and rejections.
* Provide an explanation for important recommendations.
* Allow authorized users to review automation history.

14.7 Future Smart Locker Integration

Smart pickup lockers will be a future BlackGrid hardware integration.

The software must eventually support:

* Authorized pickup verification.
* Secure compartment assignment.
* Pickup notifications.
* Locker availability monitoring.
* Pickup event records.
* Exception handling.

Hardware development will follow validation of the core software and customer demand.

15. Security, Privacy, and Regulatory Safeguards

Security and privacy are foundational requirements for BlackGrid Cannabis OS.

The platform must protect business information, customer privacy, employee accounts, and authorized system integrations.

15.1 Data Protection

* Encrypt information during transmission.
* Use secure storage for sensitive information.
* Protect database access.
* Secure API credentials.
* Apply least-privilege access.
* Maintain backup and recovery procedures.

15.2 Organization Separation

* Prevent unauthorized access between organizations.
* Enforce database-level access controls.
* Apply location-specific permissions.
* Test for cross-organization data exposure.
* Keep supplier and dispensary information appropriately separated.

15.3 Customer Privacy

* Collect only information necessary for the requested functionality.
* Minimize storage of personally identifiable information.
* Do not expose customer-identifying information in supplier analytics.
* Establish data retention and deletion policies.
* Restrict access to customer records.

15.4 Employee Access

* Support role-based permissions.
* Require authenticated access.
* Record important account and administrative actions.
* Support access revocation.
* Protect sensitive administrative functions.

15.5 Regulatory Compatibility

BlackGrid must support jurisdiction-specific requirements.

The system must:

* Respect applicable state and local regulations.
* Use authorized integrations with regulatory systems.
* Maintain accurate records.
* Support audit and reporting workflows.
* Avoid unauthorized changes to regulated records.
* Keep regulatory rules configurable by jurisdiction.

BlackGrid is an operational software platform and does not replace state tracking systems, legal counsel, or the licensee’s compliance obligations.

15.6 Integration Security

* Use authorized provider credentials.
* Follow provider API permissions and rate limits.
* Protect integration secrets.
* Monitor synchronization failures.
* Maintain integration audit records.
* Support credential revocation.

15.7 Security Testing

Before production deployment, BlackGrid must undergo:

* Authentication testing.
* Permission testing.
* Database security testing.
* Cross-tenant isolation testing.
* API security testing.
* Backup and recovery testing.
* Vulnerability assessment.

15.8 Incident Management

The platform should support:

* Security event logging.
* Incident investigation.
* Access revocation.
* Recovery procedures.
* Appropriate customer notification processes.

16. BlackGrid Visual Identity and User Experience

16.1 Design Direction

BlackGrid Cannabis OS will use a hybrid luxury enterprise interface with electric green and attention red accents.

The visual identity should communicate:

* Professionalism.
* Innovation.
* Technology.
* Trust.
* Efficiency.
* Financial intelligence.

16.2 Color Palette

Primary colors:

* Charcoal black.
* Deep graphite.
* Clean white.
* Soft gray.

Accent colors:

Electric Green

* Positive financial performance.
* Profit growth.
* Verified savings.
* Successful operations.
* Completed tasks.
* Positive business opportunities.

Attention Red

* Critical alerts.
* Urgent warnings.
* Inventory discrepancies.
* Compliance concerns requiring review.
* Financial losses and declining margins.
* Overdue tasks.
* Security warnings.
* Important notifications.
* Actions requiring immediate attention.

Red must be visually prominent enough to attract attention without overwhelming the interface.

16.3 Alert Priority System

BlackGrid will support three levels of alerts:

* Critical: Red. Immediate attention or action required.
* Warning: Amber or orange. Potential problems requiring review.
* Informational: Neutral gray. Updates and general notifications.

Critical alerts should be easy to identify from the main dashboard.

16.4 Interface Style

The platform will combine:

* Dark navigation and sidebars.
* Clean, light workspace areas.
* Premium dashboard cards.
* Modern data tables.
* Clear charts and graphs.
* Simple navigation.
* Consistent typography.
* Responsive layouts.

16.5 Main Navigation

Initial navigation:

1. Overview.
2. Intelligence.
3. Inventory.
4. Profit Leak Detector.
5. Promotions.
6. Vendors.
7. Procurement.
8. Compliance.
9. Customer Experience.
10. Automation.
11. Settings.

Navigation must respect user permissions and available business modules.

16.6 Dashboard Experience

The main dashboard should provide:

* Business performance overview.
* Sales and profitability metrics.
* Inventory alerts.
* Promotion performance.
* Vendor opportunities.
* Potential savings.
* Important operational notifications.

Critical information must stand out through red indicators, alert badges, warning icons, and clear notification placement.

16.7 User Experience Principles

* Make complex business information easy to understand.
* Prioritize actionable insights over unnecessary charts.
* Provide explanations for financial calculations.
* Allow users to investigate underlying data.
* Support desktop, tablet, and mobile devices.
* Make important actions easy to find.
* Maintain accessibility and readable contrast.
* Never rely on color alone to communicate an alert or status.

16.8 Brand Consistency

All BlackGrid modules, future mobile experiences, kiosks, and smart locker interfaces should follow a consistent visual identity.

BlackGrid should look and feel like one connected technology ecosystem.

17. Role-Based Dashboard Experience

BlackGrid will provide customized dashboards based on each user’s organization, role, and assigned permissions.

17.1 Owner Dashboard

The owner dashboard will prioritize business performance and financial intelligence.

Features:

* Daily, weekly, and monthly sales.
* Gross profit and profit margins.
* Revenue trends.
* Product profitability.
* Profit Leak Detector alerts.
* Vendor savings opportunities.
* Promotion performance.
* Multi-location comparisons.
* Business health overview.
* Critical business notifications.

17.2 Manager Dashboard

The manager dashboard will prioritize daily dispensary operations.

Features:

* Inventory alerts.
* Products requiring attention.
* Daily operational tasks.
* Order preparation status.
* Purchasing recommendations.
* Promotion activity.
* Operational discrepancies.
* Employee task assignments.
* Important notifications.

17.3 Employee Dashboard

The employee dashboard will prioritize assigned responsibilities.

Features:

* Assigned tasks.
* Restocking notifications.
* Order preparation workflows.
* Customer service tasks.
* Relevant operational alerts.

Employees must only access information and actions authorized for their role.

17.4 Administrator Dashboard

Administrators will have access to authorized system management tools.

Features:

* User management.
* Role and permission management.
* Location configuration.
* Integration status.
* Synchronization monitoring.
* Audit history.
* System settings.

17.5 Multi-Location Owner Experience

Owners authorized to manage multiple locations will be able to:

* View consolidated business performance.
* Compare individual locations.
* Identify differences in product performance.
* Compare inventory levels.
* Review location-specific alerts.
* Identify opportunities across their organization.

17.6 Dashboard Security

* Dashboard views must respect role-based permissions.
* Users must not access unauthorized financial information.
* Organization and location boundaries must be enforced.
* Dashboard data must reflect authorized source information.
* Users must not be able to bypass permissions by changing URLs or frontend settings.

The objective is to give every user the information they need to perform their job without exposing information they do not need.

18. Financial Intelligence — Calculation Rules

18.1 Purpose

BlackGrid Financial Intelligence will convert dispensary transaction, inventory, purchasing, and promotion data into accurate financial information that helps business owners understand profitability, identify financial leaks, and make better operating decisions.

18.2 Core Financial Metrics

The platform must support the following calculations:

* Gross Sales: Total recorded product sales before discounts and returns.
* Discounts: Total reductions applied to product sales.
* Returns: Total reversed or refunded sales.
* Net Sales: Gross Sales minus Discounts and Returns.
* Cost of Goods Sold (COGS): Recorded acquisition cost of products sold.
* Gross Profit: Net Sales minus COGS.
* Gross Margin: Gross Profit divided by Net Sales, multiplied by 100.
* Inventory Value: Recorded cost value of available inventory.

18.3 Financial Accuracy Rules

1. Never count collected taxes as ordinary sales revenue.
2. Track sales taxes, excise taxes, and other tax categories separately.
3. Prevent discounts and returns from being deducted more than once.
4. Distinguish actual recorded costs from estimated costs.
5. Never present estimated profit as confirmed profit.
6. If product cost information is missing, identify the margin as unavailable.
7. Preserve the original transaction data and its source.
8. Support different tax and accounting configurations by jurisdiction.
9. Record the reporting period and last successful data synchronization.
10. Allow authorized users to investigate how every financial metric was calculated.

18.4 Financial Transparency

Every major financial metric should allow an authorized user to see the underlying calculation and supporting records.

BlackGrid must distinguish between:

* Actual recorded financial results.
* Estimated financial results.
* Potential savings opportunities.
* Unverified or incomplete financial information.

18.5 Business Intelligence Objective

The goal is not simply to show owners how much money their dispensary generated.

BlackGrid must help answer:

* How much money did the business actually generate?
* Which products generate the strongest gross profit?
* Which products generate high sales but weak margins?
* How much money is being given away through discounts?
* Which products are tying up inventory capital?
* Where are purchasing costs increasing?
* Where can the business potentially save money?

19. Product Profitability Intelligence

19.1 Purpose

BlackGrid must help dispensary owners understand the true financial performance of every product, brand, and product category.

The system must look beyond sales volume and identify which products generate the strongest gross profit, which products have weak margins, and which products may be hurting overall profitability.

19.2 Product-Level Financial Analysis

For each product, BlackGrid should track:

* Total units sold.
* Gross sales.
* Discounts applied.
* Returns and refunds.
* Net sales.
* Recorded cost per unit.
* Total cost of goods sold.
* Gross profit.
* Gross profit margin.
* Average selling price.
* Current inventory quantity.
* Sales velocity.

19.3 Product Profitability Classification

BlackGrid should identify products using categories such as:

* High Sales / High Profit: Strong-performing products worth monitoring and keeping in stock.
* High Sales / Low Profit: Products generating revenue but producing weak profit.
* Low Sales / High Profit: Products with strong margins but limited customer demand.
* Low Sales / Low Profit: Products that may require pricing, promotion, purchasing, or inventory review.

These classifications must be based on actual recorded data and configurable thresholds.

19.4 Profit Opportunity Detection

BlackGrid should identify opportunities such as:

* Products with unusually low gross margins.
* Products selling below their target margin.
* Products receiving excessive discounts.
* Products with rising acquisition costs.
* Products with strong sales but weak profitability.
* Products with declining average selling prices.
* Products with low sales velocity and high inventory investment.

Each opportunity should explain why it was identified and show the financial data supporting the recommendation.

19.5 Product Comparison

Owners should be able to compare:

* Products within the same category.
* Different brands.
* Different product sizes and variations.
* Products from different vendors.
* Current performance against previous reporting periods.

Comparisons must use consistent reporting periods and clearly identify missing or estimated cost information.

19.6 Recommended Actions

BlackGrid may recommend:

* Reviewing product pricing.
* Negotiating better vendor costs.
* Reducing unnecessary discounts.
* Adjusting future purchase quantities.
* Evaluating promotional opportunities.
* Reviewing products with declining demand.

Recommendations must provide supporting evidence. BlackGrid must not automatically change prices, place orders, or alter regulated inventory records without authorized approval and appropriate integrations.

19.7 Owner Dashboard Integration

The owner dashboard should highlight:

* Most profitable products.
* Highest-revenue products.
* Products with the weakest margins.
* Products with declining profitability.
* Products creating potential profit opportunities.
* Estimated financial impact of recommended actions.

Every insight must allow the owner to investigate the underlying product and transaction information.

19.8 Accuracy Requirements

Product profitability calculations must account for discounts, returns, product costs, and reporting periods without double counting.

If product costs are missing, outdated, or estimated, the system must clearly identify the limitation rather than displaying an unsupported profit figure.

20. Inventory Intelligence

20.1 Purpose

BlackGrid Inventory Intelligence will help dispensary owners understand inventory movement, product availability, inventory investment, and purchasing risks.

The goal is to reduce unnecessary inventory spending, prevent avoidable stockouts, and improve inventory efficiency.

20.2 Inventory Monitoring

For each product, BlackGrid should monitor:

* Current available quantity.
* Units sold over time.
* Units received.
* Inventory adjustments.
* Inventory aging.
* Average daily sales.
* Sales velocity.
* Recorded unit acquisition cost.
* Total inventory value.
* Last sale date.
* Last restock date.

20.3 Slow-Moving Inventory Detection

Identify products that:

* Have experienced declining sales.
* Have remained in inventory for extended periods.
* Have unusually low sales velocity.
* Have significant inventory value relative to demand.
* May require purchasing or promotional review.

Allow owners to filter by product, category, brand, location, and reporting period.

20.4 Overstock Detection

Identify products where available inventory significantly exceeds expected demand.

Show:

* Current stock quantity.
* Average daily sales.
* Estimated days of inventory remaining.
* Estimated inventory value.
* Recommended purchasing review.
* Potential capital tied up in excess inventory.

20.5 Stockout Risk Detection

Identify products that may run out before the next expected replenishment.

Consider:

* Current available inventory.
* Historical sales velocity.
* Recent demand changes.
* Supplier lead times when available.
* Pending purchase orders.
* Minimum stock thresholds.

Clearly distinguish predicted stockout risks from confirmed inventory shortages.

20.6 Inventory Forecasting

Provide configurable demand forecasts using historical sales and inventory movement.

Forecasts should:

* Identify expected demand.
* Estimate future inventory requirements.
* Highlight seasonal or unusual sales patterns when supported by data.
* Show confidence levels and data limitations.
* Avoid presenting predictions as guaranteed outcomes.

20.7 Inventory Financial Intelligence

Connect inventory information to Financial Intelligence and Product Profitability.

Show:

* Total recorded inventory investment.
* Inventory value by category and brand.
* Capital tied up in slow-moving products.
* Potential losses from declining product demand.
* Products with strong profitability and low stock.
* Products with weak profitability and excessive stock.

20.8 Recommended Inventory Actions

BlackGrid may recommend:

* Reviewing future purchase quantities.
* Reviewing supplier alternatives.
* Evaluating promotional opportunities.
* Investigating inventory discrepancies.
* Reviewing products approaching expiration or other applicable inventory deadlines.
* Prioritizing replenishment of products with strong demand.

Recommendations must be supported by recorded data.

20.9 Human Approval and Compliance

BlackGrid must not independently adjust regulated inventory records, transfer cannabis products, or execute regulated inventory transactions.

Any regulated inventory action must follow applicable state requirements and authorized system workflows.

Inventory recommendations and forecasts are decision-support tools, not replacements for required state tracking systems or licensee responsibilities.

20.10 Owner Dashboard Integration

The owner dashboard should display:

* Products running low.
* Products at risk of stockout.
* Slow-moving inventory.
* Overstock opportunities.
* Total inventory value.
* Inventory investment by category.
* Recommended purchasing reviews.
* Inventory discrepancies requiring investigation.

21. Vendor and Purchasing Intelligence

21.1 Purpose

BlackGrid Vendor and Purchasing Intelligence will help dispensaries compare suppliers, evaluate vendor offers, monitor purchasing costs, and make informed procurement decisions.

The objective is to reduce purchasing costs, improve supplier relationships, and increase business profitability.

21.2 Vendor Management

Maintain vendor profiles containing:

* Vendor name and contact information.
* Products and brands supplied.
* Available product categories.
* Historical purchase prices.
* Order history.
* Delivery lead times.
* Minimum order requirements.
* Vendor promotions and special offers.
* Authorized business relationship information.

21.3 Vendor Price Intelligence

Compare recorded acquisition costs for equivalent products across authorized vendors.

Identify:

* Products available at lower prices from alternative vendors.
* Vendors with increasing prices.
* Historical price changes.
* Unusual price differences.
* Potential purchasing savings.
* Vendor offers that may improve gross margins.

Comparisons must account for product size, quantity, quality attributes, and other relevant differences. BlackGrid must not treat non-equivalent products as identical.

21.4 Purchasing Recommendations

Combine inventory forecasts, product profitability, and vendor pricing to recommend purchasing decisions.

Recommendations should consider:

* Current inventory.
* Sales velocity.
* Forecasted demand.
* Available vendor pricing.
* Supplier lead times.
* Minimum order quantities.
* Available purchasing budget.
* Product profitability.
* Existing purchase orders.

21.5 Automated Purchase Order Preparation

BlackGrid should be able to prepare draft purchase orders using approved purchasing recommendations.

Draft orders should include:

* Vendor information.
* Recommended products.
* Quantities.
* Unit costs.
* Estimated order totals.
* Available promotions.
* Expected inventory impact.

An authorized employee must review and approve orders before submission.

21.6 Vendor Deal Intelligence

Track vendor-provided offers, including:

* Volume discounts.
* Bulk purchasing offers.
* Temporary price reductions.
* Product bundles.
* Promotional incentives.
* Special purchasing arrangements.

Evaluate whether an offer creates genuine financial value after considering inventory demand, product profitability, and purchasing requirements.

21.7 Purchasing Performance

Provide reports showing:

* Total purchasing spend.
* Spending by vendor.
* Average acquisition cost.
* Price changes over time.
* Estimated savings from alternative offers.
* Purchasing trends.
* Vendor order history.
* Purchase order performance.

21.8 Two-Sided Vendor Opportunities

Design the architecture to eventually support a supplier-facing portal where authorized vendors can:

* Submit product offers.
* Share available promotions.
* Update approved product pricing.
* Communicate purchasing opportunities.
* Review their own authorized business performance information.

Dispensary financial information and purchasing data must remain private unless explicitly authorized for sharing.

21.9 Financial Impact Measurement

For every purchasing recommendation, show:

* Current recorded cost.
* Alternative available cost.
* Quantity being evaluated.
* Potential savings.
* Expected impact on gross margin.
* Assumptions and limitations.

Clearly distinguish potential savings from savings actually achieved.

21.10 Security and Approval

Only authorized users may access vendor information, purchasing recommendations, and purchase orders.

BlackGrid must maintain an audit history of purchasing decisions, approvals, changes, and submissions.

The platform must not independently execute purchases or regulated cannabis transfers without authorized human approval and appropriate integrations.

22. Promotions and Deal Intelligence

22.1 Purpose

BlackGrid Promotions Intelligence will evaluate vendor promotions, dispensary discounts, product deals, and promotional campaigns to determine their actual financial impact.

The objective is to help dispensaries increase profitable sales, reduce unnecessary discounting, and identify promotions that benefit both the business and its customers.

22.2 Promotion Management

Track promotions with information such as:

* Promotion name and description.
* Participating products and brands.
* Vendor or dispensary providing the promotion.
* Start and end dates.
* Discount type and amount.
* Eligibility requirements.
* Participating locations.
* Applicable product categories.
* Promotion limits and restrictions.

22.3 Promotion Performance

Measure:

* Units sold during promotions.
* Gross sales.
* Discounts applied.
* Net sales.
* Cost of goods sold.
* Gross profit.
* Gross margin.
* Average transaction value.
* Redemption volume.
* Performance compared with an appropriate baseline.

22.4 Promotion Profitability Analysis

Determine whether promotions are producing meaningful financial value.

Identify:

* Promotions generating profitable incremental sales.
* Promotions increasing sales but reducing gross profit.
* Products receiving excessive discounts.
* Promotions with low customer participation.
* Promotions that primarily discount purchases customers would have made anyway.
* Promotions that help move slow-moving inventory.

Do not automatically interpret increased sales volume as increased profitability.

22.5 Vendor Promotion Intelligence

Track vendor-provided offers and evaluate their potential value to dispensaries.

Compare:

* Regular acquisition cost.
* Promotional acquisition cost.
* Required purchase quantity.
* Available inventory.
* Expected demand.
* Product profitability.
* Potential savings.

Identify offers that genuinely improve purchasing economics instead of encouraging unnecessary purchases.

22.6 Customer Savings Intelligence

Create a customer-facing experience that can eventually help customers discover:

* Available product deals.
* Eligible discounts.
* Participating brands.
* Product promotions.
* Relevant savings opportunities.

Only display promotions that are valid, authorized, and available at the selected licensed dispensary.

All customer-facing features must follow applicable advertising, age-verification, privacy, and cannabis marketing requirements.

22.7 Two-Sided Savings Intelligence

BlackGrid should evaluate promotional value from two perspectives:

Dispensary perspective:

* Increased profitability.
* Reduced discount waste.
* Better inventory movement.
* Improved vendor purchasing economics.
* More effective promotional spending.

Customer perspective:

* Available discounts.
* Eligible product deals.
* Clear promotion requirements.
* Accurate savings information.
* Easier discovery of relevant offers.

The platform must not expose private dispensary financial information to customers or vendors.

22.8 Promotion Recommendations

BlackGrid may recommend:

* Adjusting discount amounts.
* Changing promotion duration.
* Targeting specific products.
* Reviewing underperforming promotions.
* Evaluating vendor-sponsored offers.
* Avoiding discounts on products already selling strongly.
* Testing alternative promotional strategies.

Recommendations must include supporting data and estimated financial impact.

22.9 Promotion Reporting

Provide reports showing:

* Best-performing promotions.
* Least profitable promotions.
* Total discount spending.
* Estimated incremental gross profit.
* Customer savings.
* Vendor-sponsored savings.
* Promotion redemption trends.
* Performance by location, brand, and product category.

Clearly distinguish estimated incremental results from confirmed financial results.

22.10 Approval and Compliance

Authorized employees must approve promotions before publication or activation.

BlackGrid must not independently publish cannabis advertisements, change regulated pricing, or execute promotional transactions without appropriate authorization and applicable regulatory safeguards.

Maintain an audit history of promotion creation, approval, changes, and performance.

23. Compliance and Audit Intelligence

23.1 Purpose

BlackGrid Compliance Intelligence will help licensed cannabis businesses monitor operational records, identify potential discrepancies, organize compliance-related information, and maintain an accessible history of important business activities.

The objective is to reduce administrative work, improve record visibility, and help businesses identify issues that require attention.

23.2 Compliance Monitoring

Monitor authorized business data for potential issues, including:

* Inventory discrepancies.
* Differences between POS and inventory records.
* Missing or incomplete transaction information.
* Unusual inventory adjustments.
* Incomplete product records.
* Missing supporting documentation.
* Unresolved synchronization errors.
* Inconsistent records between connected systems.

23.3 Compliance Alerts

Generate alerts based on configurable rules and authorized data.

Alert categories should include:

* Critical: Potentially serious discrepancies requiring immediate investigation.
* Warning: Issues requiring employee or management review.
* Informational: Record updates, synchronization notices, and routine reminders.

Every alert should explain what was detected, which records are involved, when it occurred, and what action may be appropriate.

23.4 Audit History

Maintain searchable records of important activities, including:

* User actions.
* Inventory-related changes.
* Purchasing approvals.
* Promotion approvals.
* Integration activity.
* Data synchronization events.
* Alert acknowledgments.
* Administrative changes.

Audit records should identify the responsible user or system, timestamp, affected record, and relevant change information when available.

23.5 Record Organization

Provide authorized users with tools to organize and retrieve:

* Business records.
* Transaction references.
* Inventory records.
* Vendor documentation.
* Purchase orders.
* Compliance-related documents.
* Alert histories.
* System activity reports.

Support secure document access and configurable retention policies.

23.6 Integration Monitoring

Monitor authorized connections with external systems, including POS platforms and approved regulatory tracking integrations.

Display:

* Connection status.
* Last successful synchronization.
* Synchronization errors.
* Missing or delayed data.
* Failed imports.
* Data discrepancies.
* Integration activity history.

Clearly identify the original data source for every imported record.

23.7 Compliance Investigation Workflow

Allow authorized employees to:

1. Review an alert.
2. Examine supporting records.
3. Assign an investigation.
4. Add internal notes.
5. Attach supporting documentation.
6. Record the investigation outcome.
7. Escalate unresolved issues.
8. Maintain a complete investigation history.

23.8 Compliance Reporting

Provide reports that help management review:

* Open compliance alerts.
* Resolved discrepancies.
* Outstanding investigations.
* Inventory reconciliation issues.
* Integration failures.
* Employee activity history.
* Documentation status.

Reports must distinguish verified findings from suspected issues.

23.9 Security and Access Control

Restrict sensitive compliance records to authorized users.

Maintain organization and location-level access permissions, audit sensitive access, and protect records against unauthorized modification or disclosure.

23.10 Regulatory Boundaries

BlackGrid is an operational monitoring and decision-support platform.

It does not replace Metrc, Michigan Cannabis Regulatory Agency systems, required state reporting, licensee responsibilities, or professional legal and compliance advice.

Any future regulatory integration must be officially supported, authorized, securely implemented, and validated before production use.

BlackGrid must never independently submit regulated transactions, alter official tracking records, or represent an unverified activity as compliant.

23.11 Owner Dashboard Integration

Display:

* Critical compliance alerts.
* Inventory discrepancies.
* Unresolved investigations.
* Integration health.
* Recent audit activity.
* Outstanding documentation tasks.

Give owners a clear view of issues requiring attention without overwhelming them with routine system notifications.


24. Customer Experience and Self-Service Intelligence

24.1 Purpose

BlackGrid Customer Experience will provide licensed dispensaries with customer-facing digital tools that simplify product discovery, promotion discovery, order preparation, check-in, and pickup workflows.

The objective is to improve the customer experience while reducing repetitive employee tasks and improving operational efficiency.

24.2 Digital Product Discovery

Provide a customer-facing catalog that can display authorized product information, including:

* Product names and descriptions.
* Brands and categories.
* Product availability.
* Approved product images.
* Current authorized pricing.
* Applicable promotions.
* Product specifications and attributes.

Product information must synchronize with authorized business systems and reflect data freshness.

24.3 Customer Deal Discovery

Help customers identify legitimate available savings.

Customers should be able to:

* Browse active promotions.
* Discover eligible product deals.
* Compare applicable offers.
* Review promotion requirements.
* Understand potential savings.

Only valid, authorized promotions should be displayed.

24.4 Digital Check-In

Design a digital check-in workflow that can reduce repetitive front-desk tasks.

Potential capabilities include:

* Customer arrival notification.
* Secure identity verification through approved systems.
* Appointment or order lookup.
* Eligibility verification through authorized processes.
* Queue status.
* Employee notification.
* Check-in completion history.

The system must protect customer identity information and avoid storing unnecessary sensitive data.

24.5 Order Preparation

Allow customers to prepare orders through approved workflows before arriving or while at the dispensary.

Potential capabilities include:

* Product selection.
* Availability checks.
* Promotion eligibility.
* Order review.
* Order submission for employee review.
* Order status notifications.
* Employee preparation queues.

Orders must remain subject to applicable laws, inventory availability, age and eligibility verification, and dispensary approval.

24.6 Customer Self-Service Kiosks

Design the software architecture to support future in-store kiosks.

Potential kiosk functions include:

* Customer check-in.
* Product catalog browsing.
* Promotion discovery.
* Order lookup.
* Digital order preparation.
* Pickup status.
* Employee assistance requests.

Kiosks must provide accessible alternatives for customers who need employee assistance.

24.7 Employee Efficiency

Reduce repetitive tasks by allowing authorized automation to handle appropriate workflow steps.

Examples include:

* Customer arrival notifications.
* Order status updates.
* Pickup queue management.
* Digital catalog updates.
* Promotion information display.
* Routine customer notifications.
* Employee task routing.

Employees must retain control over activities requiring human judgment, identity verification, approval, or regulated transactions.

24.8 Customer Privacy and Security

Protect customer information through:

* Minimal data collection.
* Secure identity verification.
* Role-based access.
* Encryption.
* Configurable data retention.
* Secure session handling.
* Access logging.
* Protection against unauthorized disclosure.

Do not expose customer purchasing histories or personal information to unauthorized employees, vendors, or other dispensaries.

24.9 Accessibility and Usability

Customer-facing experiences should be simple, mobile-friendly, accessible, and easy to understand.

Support customers who prefer traditional employee-assisted service.

24.10 Future Pickup Integration

Design for future integration with secure smart pickup lockers.

Potential functionality includes:

* Approved order completion notifications.
* Secure pickup authorization.
* One-time pickup codes or tokens.
* Locker assignment.
* Pickup status tracking.
* Time-stamped access events.
* Employee exception handling.

Any locker-based cannabis handoff must follow applicable identity verification, age verification, security, custody, and regulatory requirements.

24.11 Business Intelligence

Measure operational performance without unnecessarily collecting personal customer information.

Potential metrics include:

* Average check-in time.
* Average order preparation time.
* Customer wait time.
* Self-service utilization.
* Employee task reduction.
* Order completion time.
* Promotion engagement.
* Customer experience feedback.

24.12 Owner Dashboard Integration

Provide owners and managers with visibility into:

* Customer check-in activity.
* Orders awaiting preparation.
* Pickup queue status.
* Self-service utilization.
* Employee workload indicators.
* Average wait times.
* Workflow bottlenecks.

25. Smart Automation and Pickup Locker Intelligence

25.1 Purpose

BlackGrid Smart Automation will provide the software foundation for future automated dispensary workflows, including smart pickup lockers, customer check-in stations, and self-service kiosks.

The objective is to reduce repetitive employee tasks, improve pickup efficiency, and allow dispensary employees to focus on in-person customer service.

25.2 Smart Pickup Locker Architecture

Design a centralized software platform capable of communicating with compatible smart locker hardware.

The platform should support:

* Individual locker identification.
* Locker availability monitoring.
* Secure locker assignment.
* Locker status monitoring.
* Order-to-locker association.
* Pickup authorization.
* Time-stamped access records.
* Remote status visibility.
* Hardware connectivity monitoring.

25.3 Customer Pickup Workflow

Design the following future workflow:

1. An authorized employee completes the required order review and approval.
2. The system confirms that the order is eligible for the approved pickup workflow.
3. An authorized process verifies the customer’s identity and eligibility.
4. The system assigns an available locker when permitted.
5. The customer receives a secure pickup notification.
6. The customer arrives and completes the required verification.
7. The system authorizes access to the assigned locker.
8. The customer retrieves the approved order.
9. The system records the pickup event.
10. The order is marked completed through an authorized workflow.

No locker should open based solely on possession of an order number or notification.

25.4 Identity and Pickup Security

Support secure integration with approved identity verification and access-control systems.

Security requirements include:

* Appropriate customer identity and eligibility verification.
* Unique, time-limited pickup credentials.
* Secure authorization.
* Protection against credential sharing and reuse.
* Locker access logging.
* Failed access attempt monitoring.
* Emergency access procedures.
* Employee override with authorization and audit history.

25.5 Hardware Monitoring

Monitor connected locker equipment for:

* Online or offline status.
* Door status.
* Lock status.
* Temperature where applicable.
* Power status.
* Network connectivity.
* Hardware errors.
* Maintenance requirements.

Notify authorized employees when a locker requires attention.

25.6 Employee Management Console

Provide employees with a centralized interface to:

* View active locker assignments.
* Monitor pickup activity.
* Identify incomplete pickups.
* Investigate access failures.
* Release lockers through authorized procedures.
* Handle customer assistance requests.
* Review equipment alerts.

25.7 Automation and Labor Efficiency

Measure how automation affects dispensary operations.

Track:

* Number of completed automated pickups.
* Average pickup time.
* Employee-assisted versus self-service pickups.
* Employee interventions.
* Failed pickup attempts.
* Equipment downtime.
* Estimated employee time saved.

Clearly distinguish estimated time savings from measured time savings.

25.8 Multi-Vendor Hardware Compatibility

Build a modular integration architecture that can support different locker manufacturers and kiosk hardware providers.

Use standardized device communication interfaces where available.

Avoid making BlackGrid dependent on a single hardware manufacturer.

25.9 Security and Regulatory Boundaries

Smart lockers are not independent authorization systems.

Every regulated product handoff must follow applicable state and local requirements, including any required employee supervision, identity verification, transaction processing, and inventory tracking.

BlackGrid must not bypass required POS workflows, state tracking systems, or licensee responsibilities.

Any production locker integration must undergo security, operational, and regulatory validation before deployment.

25.10 Owner Dashboard Integration

Provide visibility into:

* Active locker assignments.
* Completed pickups.
* Pending pickups.
* Failed access attempts.
* Hardware availability.
* Equipment alerts.
* Automated pickup volume.
* Employee intervention rates.
* Estimated labor savings.

26. Multi-Location and Nationwide Intelligence

26.1 Purpose

BlackGrid must support cannabis businesses operating one or multiple licensed locations across different jurisdictions.

The objective is to provide centralized business intelligence while allowing each location to maintain its own operational controls, financial records, permissions, and regulatory requirements.

26.2 Multi-Location Management

Allow authorized organizations to:

* Add and manage multiple dispensary locations.
* Assign employees to specific locations.
* Configure location-specific permissions.
* Monitor individual location performance.
* Compare business performance across locations.
* View consolidated organizational reports.
* Manage location-specific integrations.
* Configure location-specific operational settings.

26.3 Centralized Owner Dashboard

Provide multi-location owners with a centralized dashboard showing:

* Total organizational sales.
* Net sales by location.
* Gross profit by location.
* Gross margin comparisons.
* Inventory value.
* Purchasing expenditures.
* Promotion performance.
* Operational alerts.
* Compliance investigation status.
* Location performance rankings.

Owners should be able to move from organizational summaries into individual location details.

26.4 Location Comparisons

Allow authorized users to compare locations using:

* Sales performance.
* Product profitability.
* Inventory turnover.
* Discount spending.
* Purchasing costs.
* Promotion effectiveness.
* Customer wait times.
* Operational efficiency.

Comparisons must account for differences in reporting periods, product availability, and local operating conditions.

26.5 Nationwide Regulatory Configuration

Design BlackGrid to support different state and local regulatory environments.

Each jurisdiction may have different requirements involving:

* Cannabis licensing.
* Product classifications.
* Tax structures.
* Advertising restrictions.
* Inventory tracking.
* Transaction reporting.
* Customer eligibility.
* Delivery and pickup procedures.
* Record retention.

Regulatory configurations must be jurisdiction-specific and maintained through a controlled update process.

BlackGrid must not assume that a workflow permitted in one state is permitted in another.

26.6 Integration Flexibility

Support different POS providers, inventory systems, approved regulatory integrations, and hardware providers across locations.

Each connection must have its own:

* Authorization.
* Credentials.
* Synchronization configuration.
* Error monitoring.
* Data mapping.
* Audit history.

The system should use a standardized integration architecture while respecting provider-specific and jurisdiction-specific requirements.

26.7 Organization and Data Separation

Maintain strict separation between organizations and their respective locations.

Requirements include:

* Organization-level data isolation.
* Location-level access permissions.
* Role-based authorization.
* Secure integration credentials.
* Auditable administrative actions.
* Controlled cross-location reporting.
* Protection against unauthorized data sharing.

Employees should only access information permitted by their assigned roles and organizational permissions.

26.8 Cross-Location Intelligence

Identify business opportunities across an organization’s locations.

Examples include:

* Products performing well at one location but poorly at another.
* Differences in vendor acquisition costs.
* Locations experiencing repeated stockouts.
* Locations carrying excessive slow-moving inventory.
* Promotions producing different results across locations.
* Operational processes that could be improved.

Recommendations must consider local market conditions and applicable regulatory restrictions.

26.9 Nationwide Business Intelligence

Design future capabilities that can help authorized operators understand broader business trends across their own operations.

Potential capabilities include:

* Multi-state financial reporting.
* Consolidated inventory intelligence.
* Cross-location vendor comparisons.
* Purchasing optimization.
* Promotion performance analysis.
* Operational benchmarking.
* Jurisdiction-specific reporting.

Any external benchmarking must use appropriately authorized and privacy-protected information.

26.10 Owner Dashboard Integration

Provide organizational owners with:

* Enterprise-wide performance summaries.
* Location-level comparisons.
* State and jurisdiction filters.
* Consolidated financial intelligence.
* Cross-location savings opportunities.
* Location-specific alerts.
* Organization-wide operational reporting.

The experience must remain useful for both a single-location independent dispensary and a large multi-location operator.

27. Minimum Viable Product (MVP) Definition

27.1 Purpose

The BlackGrid Cannabis OS MVP will establish the first functional version of the platform.

The objective is to deliver a useful business intelligence system that helps dispensary owners understand sales performance, product profitability, inventory conditions, and promotional effectiveness.

The MVP must prioritize accuracy, usability, security, and measurable business value over the number of features.

27.2 Initial Target Customers

The initial MVP will target:

* Independent licensed cannabis dispensaries.
* Small and medium-sized dispensary operators.
* Multi-location operators interested in centralized business intelligence.

Michigan will be the initial target market, while the architecture will remain adaptable to additional states.

27.3 Core MVP Modules

The initial release will prioritize:

1. Owner Dashboard: Centralized business performance overview.
2. Sales Intelligence: Sales trends, product performance, and revenue reporting.
3. Product Profitability: Product-level gross profit and margin analysis.
4. Inventory Guardian: Inventory levels, sales velocity, slow-moving products, and stockout warnings.
5. Promotions Intelligence: Discount analysis and promotional performance.
6. Vendor Intelligence: Basic vendor and acquisition-cost comparisons.
7. Compliance Monitoring: Read-only operational alerts and synchronization monitoring.
8. Integrations Center: Connection management and data synchronization status.

27.4 Initial Data Integration

The platform must support a standardized POS integration architecture.

The first development milestone will use a simulated POS connector with realistic sample data.

The architecture must also support future authorized direct POS integrations and approved third-party integration providers.

Production connections must require appropriate provider authorization, secure credentials, and validation.

27.5 Initial Owner Experience

The first owner dashboard must display:

* Gross sales.
* Net sales.
* Gross profit.
* Gross margin.
* Discounts.
* Inventory value.
* Best-selling products.
* Least profitable products.
* Slow-moving inventory.
* Potential savings opportunities.
* Important operational alerts.

All demonstration data must be clearly identified as fictional.

27.6 Initial Manager Experience

The MVP should provide a manager-oriented experience focused on:

* Daily sales performance.
* Inventory conditions.
* Products requiring attention.
* Promotion performance.
* Purchasing recommendations.
* Operational alerts.

Access must be restricted according to assigned permissions.

27.7 MVP Exclusions

The initial release will not include:

* Live cannabis transactions.
* Payment processing.
* Direct regulated inventory adjustments.
* Automatic purchase order submission.
* Production smart locker operations.
* Automated customer identity verification.
* Unapproved regulatory system integrations.
* Nationwide regulatory automation.

These capabilities will be evaluated for later development after the foundational platform is validated.

27.8 Technical Development Priorities

The MVP must establish:

* Secure user authentication.
* Organization and location management.
* Role-based access control.
* Database security and tenant isolation.
* Reusable user interface components.
* Financial calculation services.
* POS connector architecture.
* Data synchronization monitoring.
* Audit logging.
* Responsive desktop and mobile experiences.

27.9 MVP Validation

Before considering the MVP ready for a real customer pilot, validate:

* Financial calculations against source records.
* Product profitability calculations.
* Inventory quantity accuracy.
* Duplicate transaction prevention.
* Data synchronization reliability.
* User permissions.
* Organization data isolation.
* Alert accuracy.
* Dashboard reporting.
* Error handling.

27.10 First Working Milestone

The first working milestone will be a demonstration dispensary that can:

1. Sign in securely.
2. View a fictional dispensary workspace.
3. Import sample products.
4. Import simulated sales transactions.
5. Calculate sales and gross profit.
6. Identify best-selling and least profitable products.
7. Display inventory conditions.
8. Analyze promotional performance.
9. Identify potential savings opportunities.
10. View synchronization status and operational alerts.

27.11 Product Development Philosophy

Build the smallest reliable version that demonstrates meaningful business value.

Prioritize measurable improvements in profitability, inventory efficiency, purchasing decisions, and employee productivity.

Do not sacrifice data accuracy, security, or regulatory safeguards to accelerate development.

## 28. Testing, Validation and Quality Assurance

### 28.1 Purpose

BlackGrid must undergo structured testing before being introduced into production environments.

The objective is to ensure that financial calculations, inventory intelligence, integrations, permissions, and reporting are accurate, reliable, and secure.

### 28.2 Financial Accuracy Testing

Validate:
- Gross sales calculations.
- Net sales calculations.
- Discounts and returns.
- Cost of goods sold.
- Gross profit.
- Gross margins.
- Inventory valuation.
- Product-level profitability.

Compare BlackGrid calculations against independently verified source records.

### 28.3 POS Integration Testing

Test:
- Successful data imports.
- Duplicate transaction prevention.
- Missing transaction detection.
- Product identification and mapping.
- Inventory synchronization.
- Delayed synchronization.
- Failed connections.
- Recovery after connection interruptions.

Every imported record must retain its source reference.

### 28.4 Inventory Testing

Validate:
- Inventory quantities.
- Inventory adjustments.
- Units sold.
- Inventory valuation.
- Sales velocity.
- Slow-moving product detection.
- Overstock warnings.
- Stockout predictions.

### 28.5 Intelligence Testing

Evaluate whether BlackGrid correctly identifies:
- High-revenue, low-margin products.
- Unprofitable promotions.
- Excessive discounts.
- Potential purchasing savings.
- Slow-moving inventory.
- Unusual financial changes.

Recommendations must be explainable and supported by underlying data.

### 28.6 Security Testing

Test:
- Authentication.
- Password and session security.
- Role-based permissions.
- Organization data isolation.
- Location-level permissions.
- API security.
- Integration credential protection.
- Audit logging.

### 28.7 User Experience Testing

Evaluate:
- Dashboard usability.
- Navigation.
- Mobile responsiveness.
- Accessibility.
- Notification visibility.
- Report readability.
- Ease of understanding financial insights.

### 28.8 Performance Testing

Test:
- Dashboard loading.
- Large transaction imports.
- Multiple locations.
- Database query performance.
- Concurrent users.
- Integration synchronization.
- Report generation.

### 28.9 Pilot Validation

Before commercial launch, conduct controlled testing with authorized cannabis businesses.

Pilot participants should evaluate:
- Financial accuracy.
- Inventory accuracy.
- Usefulness of recommendations.
- Time saved.
- Ease of operation.
- Reliability.
- Overall business value.

Use fictional or appropriately authorized test data during development.

### 28.10 Issue Management

Maintain a documented process for:
- Recording defects.
- Assigning priorities.
- Investigating causes.
- Tracking corrections.
- Retesting fixes.
- Approving releases.

Critical financial, security, and data-integrity defects must be resolved before production deployment.

### 28.11 Release Approval

A release must not be considered production-ready until its required testing has passed and outstanding critical issues have been resolved.

Maintain version history, deployment records, and rollback procedures.

## 29. Pricing and Subscription Model

### 29.1 Business Model

BlackGrid Cannabis OS will operate as a business-to-business (B2B) software-as-a-service (SaaS) platform.

Customers will pay recurring subscription fees for access to the platform. Pricing should be predictable, transparent, and scalable as customer organizations grow.

### 29.2 Subscription Structure

The platform should support three primary subscription tiers:

**Starter**
- Core owner dashboard
- Basic sales and financial reporting
- Product performance insights
- Basic inventory visibility
- Standard alerts
- One business location

**Professional**
- All Starter features
- Advanced financial intelligence
- Inventory intelligence
- Promotion performance reporting
- Vendor intelligence
- Expanded reporting
- Additional user roles and permissions
- Multiple locations, subject to plan limits

**Enterprise**
- All Professional features
- Advanced multi-location reporting
- Organization-wide analytics
- Expanded user and permission management
- Advanced integration capabilities
- Custom reporting
- Priority support
- Custom organizational configuration

### 29.3 Optional Add-On Services

The pricing architecture should support optional paid capabilities, including:

- Additional business locations
- Advanced analytics
- Expanded data retention
- Custom reporting
- Premium integration support
- Enterprise onboarding
- Additional administrative capabilities

Add-ons must be clearly described and priced separately.

### 29.4 Pricing Administration

Administrators should be able to configure:

- Subscription tiers
- Monthly and annual billing options
- Location limits
- User limits
- Feature access
- Trial periods
- Subscription status
- Plan upgrades and downgrades
- Account billing history

Changes to subscription settings must be recorded in an administrative audit history.

### 29.5 Scalability

The pricing system must support:

- Independent businesses
- Multi-location organizations
- Enterprise customers
- Future nationwide expansion
- Different feature packages
- Custom enterprise agreements

Pricing rules should be configurable without requiring changes to the core application architecture.

### 29.6 Billing and Security Boundaries

The platform should use an established, authorized billing provider when payment processing is introduced.

BlackGrid should not store raw payment card information.

Billing access must be restricted to authorized account owners and administrators. Subscription and billing records must be protected through appropriate security controls.

### 29.7 Pricing Strategy

Initial pricing should be designed to make adoption accessible to smaller licensed businesses while allowing revenue to grow as customers use additional capabilities and locations.

Final subscription prices will be determined through market research, operating-cost analysis, customer feedback, and product validation.

### 29.8 MVP Requirements

The initial MVP should include:

- A configurable subscription-plan structure
- Feature-access controls
- Organization and location limits
- A subscription status field
- An administrative plan-management interface

Live recurring billing is not required for the first demonstration. Subscription plans may initially be represented using simulated account data.

## 30. Customer Onboarding and Account Setup

### 30.1 Onboarding Objectives

BlackGrid Cannabis OS should provide a structured onboarding experience that helps authorized business customers configure their organization and understand the platform.

The onboarding process should be simple, secure, and scalable.

### 30.2 Organization Setup

The system should support:

- Organization name and business profile
- Primary account owner
- Authorized administrator accounts
- Business location profiles
- Organization preferences
- Subscription plan assignment
- Account status tracking

### 30.3 User Invitations and Permissions

Authorized account owners and administrators should be able to:

- Invite additional users
- Assign role-based permissions
- Manage user access
- Disable or deactivate accounts
- Review account activity

Invitations must use secure verification procedures. Users should only receive access appropriate to their assigned roles.

### 30.4 Initial Platform Configuration

The onboarding workflow should guide administrators through:

- Organization configuration
- Location setup
- User and permission configuration
- Dashboard preferences
- Reporting preferences
- Integration settings
- Notification settings

Configuration steps should clearly identify which items are required and which are optional.

### 30.5 Demo and Sample Data

New customers should be able to explore the platform using clearly labeled fictional sample data.

Sample data must remain separate from actual business records and must never be represented as verified business information.

### 30.6 Integration Readiness

The onboarding process should introduce available integration options and explain the requirements for authorized connections.

No external business system should be connected without appropriate authorization, credentials, and validation.

### 30.7 Onboarding Progress

The platform should display onboarding progress, including:

- Completed setup steps
- Incomplete setup steps
- Required administrator actions
- Configuration warnings
- Integration readiness
- Account activation status

### 30.8 Security and Audit Requirements

The onboarding system must:

- Verify account ownership and authorized administrators
- Enforce role-based permissions
- Protect organization information
- Maintain an audit history of important configuration changes
- Prevent unauthorized access between organizations
- Provide secure account recovery procedures

### 30.9 MVP Requirements

The initial MVP should include:

- Organization profile setup
- User and role configuration
- Basic location configuration
- Demo data access
- Onboarding progress indicators
- Basic account settings

Advanced automated onboarding and live external integrations may be introduced in later releases.

## 31. Notifications and Alert Management

### 31.1 Notification Objectives

BlackGrid Cannabis OS should provide a centralized notification system that communicates important business information to authorized users.

Notifications should be timely, relevant, understandable, and connected to the user's role and permissions.

### 31.2 Notification Categories

The platform should support:

- Financial performance alerts
- Unusual sales reporting changes
- Inventory data warnings
- Product profitability alerts
- Promotion performance notifications
- Vendor information updates
- Integration and synchronization errors
- Compliance monitoring alerts
- User account and security notifications
- System maintenance announcements

### 31.3 Alert Priority Levels

Notifications should support four priority levels:

**Critical**
Requires prompt administrator or authorized user attention.

**High**
Important issue requiring timely review.

**Medium**
Requires attention but may not need immediate action.

**Informational**
Provides useful updates without requiring action.

Priority must be determined by configurable rules and should not rely on color alone.

### 31.4 Role-Based Notifications

Notifications should be distributed according to user permissions:

- Owners: financial performance, business health, major alerts, and organization-wide issues.
- Managers: operational information, assigned responsibilities, and location-level alerts.
- Employees: relevant assigned tasks and permitted operational notifications.
- Administrators: account security, configuration, system health, and integration issues.

### 31.5 Notification Center

The application should include a centralized notification center with:

- Unread notification count
- Notification history
- Priority indicators
- Timestamps
- Related location or organization
- Notification descriptions
- Relevant supporting information
- Read and unread status
- Filtering and search

### 31.6 Notification Preferences

Authorized users should be able to configure:

- Notification categories
- In-app notification preferences
- Email notification preferences
- Frequency of noncritical summaries
- Quiet hours where appropriate

Critical security and account notifications must follow required security policies and cannot be disabled when doing so would compromise account protection.

### 31.7 Alert Investigation

Where appropriate, a notification should link to the relevant dashboard, report, integration status, or audit record.

The platform should explain why an alert was generated and identify the information supporting it.

### 31.8 Notification Reliability

The system should support:

- Duplicate notification prevention
- Delivery status tracking
- Retry handling for supported delivery methods
- Notification timestamps
- Error logging
- Audit history for important alerts

### 31.9 MVP Requirements

The initial MVP should include:

- In-app notification center
- Priority levels
- Read and unread status
- Role-based notification visibility
- Basic notification history
- Financial and inventory sample alerts
- Integration error notifications using simulated data

External email and advanced notification delivery can be introduced in later releases.

## 32. Reporting and Business Analytics

### 32.1 Reporting Objectives

BlackGrid Cannabis OS should provide a centralized reporting system that helps authorized business users understand performance, identify trends, and evaluate business operations.

Reports must use consistent calculation rules and clearly identify the source and reliability of their data.

### 32.2 Standard Reports

The platform should support:

- Sales performance reports
- Financial performance reports
- Product profitability reports
- Inventory performance reports
- Promotion performance reports
- Vendor comparison reports
- Location performance reports
- Integration and data quality reports
- Compliance monitoring summaries

### 32.3 Financial Reporting

Financial reports should include relevant metrics such as:

- Gross sales
- Discounts
- Returns
- Net sales
- Cost of goods sold
- Gross profit
- Gross margin
- Inventory value

Reports must follow the financial calculation rules defined in Section 18.

Estimated values must be clearly distinguished from verified source data.

### 32.4 Product and Inventory Reporting

Users with appropriate permissions should be able to review:

- Product sales trends
- Product profitability
- Inventory quantities
- Inventory movement
- Slow-moving inventory indicators
- Stock availability indicators
- Inventory valuation
- Data discrepancies

The system should identify missing or unreliable information rather than presenting unsupported calculations.

### 32.5 Comparative Analytics

The reporting system should support comparisons across:

- Selected time periods
- Business locations
- Product categories
- Individual products
- Vendors
- Organizations, where authorized

Comparisons must use consistent date ranges and calculation methods.

### 32.6 Custom Reporting

Authorized users should eventually be able to:

- Select reporting periods
- Apply available filters
- Choose supported metrics
- Save report configurations
- Reopen saved reports
- Export permitted report data

Access to sensitive information must follow organizational permissions.

### 32.7 Visualizations

Reports may include:

- Trend charts
- Bar charts
- Performance comparisons
- Distribution charts
- Summary tables
- Performance indicators

Visualizations must clearly identify their metrics, time periods, units, and data sources.

### 32.8 Scheduled Reporting

Future versions may support scheduled reports delivered to authorized users through approved channels.

Scheduling must respect account permissions, notification preferences, and data security requirements.

### 32.9 Data Export

The platform should support appropriate exports such as CSV and PDF.

Exports must:

- Respect user permissions
- Include reporting dates
- Identify the organization or location
- Identify relevant calculation definitions
- Protect confidential information
- Avoid exposing data belonging to other organizations

### 32.10 MVP Requirements

The initial MVP should include:

- Standard sales reports
- Financial performance summaries
- Product profitability reports
- Inventory reports
- Date-range filtering
- Basic location filtering
- Charts and tables
- Clearly labeled fictional demo data
- Basic CSV export using sample data

Advanced custom reporting and scheduled delivery can be introduced in later releases.

## 33. Data Management and Integration Architecture

### 33.1 Architecture Objectives

BlackGrid Cannabis OS must use a reliable, scalable data architecture that supports multiple organizations, business locations, authorized integrations, and future product expansion.

Data accuracy, security, consistency, and traceability are core requirements.

### 33.2 Data Organization

The platform should organize information using a clear hierarchy:

- Platform
- Organization
- Business location
- User
- Data source
- Business records

Each business organization must have appropriately isolated data.

### 33.3 Data Categories

The system should support organized storage and management of:

- Organization and location profiles
- User accounts and permissions
- Sales reporting data
- Product information
- Inventory reporting data
- Vendor information
- Promotion information
- Financial calculations
- Notifications and alerts
- Integration records
- Audit history
- Reporting configurations

### 33.4 Integration Architecture

BlackGrid should use a modular integration architecture.

Each external integration should have:

- A defined provider
- An authorization status
- A documented connection method
- Data mapping rules
- Synchronization settings
- Error handling
- Connection health monitoring
- Audit records

Integrations must only operate through authorized provider-supported methods.

### 33.5 Data Import and Synchronization

The platform should support:

- Structured sample-data imports
- Authorized data imports
- Scheduled synchronization where supported
- Manual synchronization requests
- Duplicate detection
- Data validation
- Missing-field detection
- Synchronization status tracking

Imported records should retain source identifiers and timestamps where available.

### 33.6 Data Quality Management

The system should identify:

- Missing information
- Invalid values
- Duplicate records
- Conflicting records
- Unexpected data changes
- Delayed synchronization
- Failed imports

Data quality issues should be visible to authorized users and should not silently produce misleading financial or operational metrics.

### 33.7 Data Mapping and Normalization

Different providers may use different formats and terminology.

BlackGrid should normalize supported data into a consistent internal structure while preserving original source information where appropriate.

Mapping changes must be traceable and testable.

### 33.8 Security and Privacy

The architecture must support:

- Organization-level data isolation
- Role-based access controls
- Encryption in transit and at rest
- Secure credential management
- Restricted administrative access
- Audit logging
- Appropriate data retention policies
- Secure backup and recovery procedures

### 33.9 Data Retention and Recovery

The platform should support configurable retention policies appropriate to the data category and applicable requirements.

Backup and recovery procedures should be documented and tested.

Important records should not be deleted without appropriate authorization and audit history.

### 33.10 API Architecture

Future versions should support documented, secured APIs for authorized integrations and approved third-party connections.

API access must include appropriate authentication, authorization, validation, rate limiting, and monitoring.

### 33.11 MVP Requirements

The initial MVP should include:

- Structured internal data models
- Organization and location data separation
- Fictional sample-data imports
- Data validation
- Duplicate detection
- Source tracking
- Simulated synchronization
- Integration status monitoring
- Basic error logging

Production integrations should be introduced only after provider authorization, security review, and validation.

## 34. Security, Privacy, and Access Control

### 34.1 Security Objectives

Security must be built into BlackGrid Cannabis OS from the beginning.

The platform must protect customer information, business records, user accounts, and system infrastructure against unauthorized access, accidental disclosure, and misuse.

### 34.2 Authentication

The platform should support:

- Secure account registration
- Verified email addresses
- Secure login procedures
- Strong password requirements
- Password recovery
- Session management
- Automatic session expiration
- Optional multi-factor authentication

### 34.3 Role-Based Access Control

The system must enforce permissions based on user roles and assigned responsibilities.

Supported roles include:

- Owner
- Manager
- Employee
- Administrator

Permissions should also be configurable at the organization and location levels.

Users must only access information and functions they are authorized to use.

### 34.4 Organization Data Isolation

Each customer organization must have isolated data access.

The system must prevent users from accessing another organization's:

- Financial information
- Product records
- Inventory records
- Vendor information
- Reports
- User accounts
- Integration credentials
- Audit records

Data isolation must be enforced by backend authorization and database policies, not merely by hiding interface elements.

### 34.5 Data Protection

The platform should implement:

- Encryption in transit
- Encryption at rest
- Secure credential storage
- Restricted access to sensitive information
- Secure handling of API credentials
- Appropriate backup protection
- Secure data deletion procedures

### 34.6 Administrative Security

Administrative capabilities should be restricted to authorized personnel.

Sensitive administrative actions should require appropriate permissions and generate audit records.

### 34.7 Audit Logging

The platform should record important security and administrative events, including:

- Successful and failed login attempts
- Permission changes
- User invitations and deactivation
- Organization configuration changes
- Integration configuration changes
- Sensitive data exports
- Administrative actions

Audit records should include timestamps and relevant actor information.

### 34.8 Privacy and Data Governance

BlackGrid should collect only information necessary to provide its services.

The platform should establish clear policies for:

- Data ownership
- Data access
- Data retention
- Data exports
- Account closure
- Data deletion
- Privacy requests
- Third-party service providers

Customer data must not be sold or shared for unrelated purposes without appropriate authorization and a valid legal basis.

### 34.9 Security Monitoring

The platform should support monitoring for:

- Unusual account activity
- Repeated authentication failures
- Unexpected permission changes
- Suspicious access patterns
- Integration credential problems
- Potential data exposure
- System security events

Security alerts should be routed to authorized personnel.

### 34.10 Incident Response

BlackGrid should maintain a documented process for:

- Identifying security incidents
- Assessing potential impact
- Containing affected systems
- Preserving relevant records
- Correcting vulnerabilities
- Communicating with affected customers when required
- Reviewing incidents to prevent recurrence

### 34.11 MVP Security Requirements

The initial MVP must include:

- Secure authentication
- Role-based permissions
- Organization-level data isolation
- Protected backend access
- Secure environment-variable handling
- Basic audit logging
- Secure session handling
- Validation of user permissions

Security testing must occur before any production customer data is introduced.

## 35. Platform Administration and System Management

### 35.1 Administration Objectives

BlackGrid Cannabis OS should include a centralized administrative environment for managing platform configuration, system health, customer accounts, and technical operations.

Administrative access must be restricted to authorized personnel.

### 35.2 Platform Administration Dashboard

The administrative dashboard should display:

- Total registered organizations
- Active and inactive accounts
- Subscription plan distribution
- Active user counts
- System health indicators
- Integration connection status
- Recent administrative activity
- Open system issues

### 35.3 Organization Management

Authorized platform administrators should be able to:

- View organization account profiles
- Review account status
- Review subscription information
- Manage account configuration
- Review organization-level support issues
- Suspend or deactivate accounts when authorized
- Review account history

Administrative access to customer business information must be limited to legitimate support and operational needs.

### 35.4 User Administration

The platform should support:

- User account status management
- Account verification status
- Role and permission review
- Account recovery support
- Session management
- Access revocation
- Administrative activity history

### 35.5 Subscription Administration

Authorized administrators should be able to manage:

- Subscription plans
- Account plan assignments
- Subscription status
- Feature entitlements
- Location limits
- User limits
- Trial configuration
- Billing provider status

Changes must be recorded in the audit history.

### 35.6 Integration Administration

The administrative environment should provide visibility into:

- Available integration providers
- Integration configuration status
- Authorization status
- Synchronization health
- Import failures
- Data validation errors
- Provider connection issues

Administrators must not bypass provider authorization or customer approval requirements.

### 35.7 System Health Monitoring

The platform should monitor:

- Application availability
- API health
- Database health
- Background job status
- Synchronization processes
- Error rates
- Performance indicators
- Backup status

### 35.8 Support and Issue Management

The platform should eventually include tools for:

- Customer support requests
- Issue categorization
- Support status tracking
- Internal notes
- Resolution history
- Escalation procedures

Sensitive customer data should not be exposed unnecessarily during support activities.

### 35.9 Configuration Management

Authorized administrators should be able to manage approved platform settings without requiring changes to the core application code.

Configuration changes must be validated, logged, and reversible where appropriate.

### 35.10 MVP Requirements

The initial MVP should include:

- Basic platform administration dashboard
- Organization account overview
- User account management
- Subscription status visibility
- Integration status monitoring
- System error visibility
- Administrative audit history

Advanced support tooling and automated infrastructure management can be introduced in later releases.

## 36. Technical Architecture and Technology Stack

### 36.1 Architecture Objectives

BlackGrid Cannabis OS should use a modern, modular, secure, and scalable architecture.

The technical foundation must support:

- Multiple customer organizations
- Multiple business locations
- Role-based user experiences
- Financial and operational analytics
- Authorized external integrations
- Secure data storage
- Future mobile experiences
- Nationwide expansion

### 36.2 Frontend Application

The frontend should provide a responsive web application that works across desktop, tablet, and mobile screen sizes.

The interface should use reusable components and a consistent design system.

The frontend should support:

- Role-specific dashboards
- Navigation and application modules
- Data tables
- Interactive charts
- Search and filtering
- Notifications
- Account settings
- Responsive layouts

### 36.3 Backend Architecture

The backend should manage:

- Authentication
- Authorization
- Organization and location management
- Business data
- Financial calculations
- Reporting
- Notifications
- Integration workflows
- Administrative operations

Sensitive calculations and permission checks must be performed or verified on the backend rather than relying exclusively on frontend logic.

### 36.4 Database Architecture

The database should support structured relational business data.

It must include appropriate relationships between:

- Organizations
- Locations
- Users
- Roles and permissions
- Products
- Sales reporting records
- Inventory records
- Vendors
- Promotions
- Financial calculations
- Notifications
- Integration records
- Audit events
- Subscription records

Organization-level data isolation must be enforced through database policies and backend authorization.

### 36.5 Recommended Initial Technology

The initial prototype may use the following technology:

- Frontend: React with TypeScript
- Application tooling: Vite
- Styling: Tailwind CSS
- UI components: reusable accessible component library
- Backend services: Supabase
- Database: PostgreSQL
- Authentication: Supabase Auth
- Source control: GitHub
- Initial interface development: Lovable

Technology choices should be reviewed as the application grows.

### 36.6 Application Architecture

The application should use a modular structure.

Major modules should include:

- Dashboard
- Sales Intelligence
- Financial Intelligence
- Inventory Intelligence
- Product Profitability
- Promotions
- Vendor Intelligence
- Reporting
- Compliance Monitoring
- Notifications
- Integrations
- Administration
- Subscription Management

Modules should share consistent data models, permissions, and design components.

### 36.7 Integration Layer

External connections should be managed through a dedicated integration layer.

The integration layer should support:

- Provider-specific connectors
- Secure authorization
- Data normalization
- Validation
- Synchronization tracking
- Error handling
- Retry management
- Integration health monitoring

Only provider-authorized and validated integrations may be used in production.

### 36.8 Development Environments

Development should use separate environments where appropriate:

- Local development
- Testing and staging
- Production

Fictional demo data must remain separate from real customer information.

Production credentials and sensitive configuration must never be committed to public source repositories.

### 36.9 Performance and Scalability

The architecture should support:

- Efficient database queries
- Pagination for large datasets
- Appropriate caching
- Background processing
- API rate limiting
- Monitoring
- Horizontal scaling where necessary

### 36.10 Technical Documentation

The project should maintain documentation covering:

- Architecture decisions
- Database structure
- API behavior
- Integration contracts
- Environment configuration
- Deployment procedures
- Testing requirements
- Security controls

### 36.11 MVP Technical Priorities

The initial MVP should prioritize:

1. Reliable application structure
2. Secure authentication
3. Organization-level data isolation
4. Core database models
5. Owner dashboard
6. Financial calculations
7. Product profitability
8. Inventory reporting
9. Fictional sample-data workflows
10. Testing and deployment readiness

Advanced infrastructure and production integrations should be introduced only when justified by validated product requirements.

## 37. Development Roadmap and Release Phases

### 37.1 Roadmap Objectives

BlackGrid Cannabis OS should be developed through organized phases.

Each phase should establish a stable foundation before additional complexity is introduced.

Development priorities should be based on customer value, technical readiness, security, and available resources.

### 37.2 Phase 1 — Foundation and Prototype

Objectives:

- Establish the application structure
- Create the core navigation
- Implement the visual design system
- Build the owner dashboard
- Create fictional demonstration data
- Establish reusable UI components
- Connect the project to GitHub
- Document initial architecture

Completion criteria:

- Application loads reliably
- Navigation works
- Dashboard displays sample information
- Layout works across common screen sizes
- Changes are tracked in source control

### 37.3 Phase 2 — Core Business Intelligence

Objectives:

- Build financial intelligence
- Implement calculation rules
- Build product profitability reporting
- Build inventory intelligence
- Add sales reporting
- Add date-range filtering
- Add dashboard visualizations

Completion criteria:

- Calculations pass validation tests
- Sample data produces consistent results
- Missing information is handled correctly
- Reports identify their data sources

### 37.4 Phase 3 — Business Operations Intelligence

Objectives:

- Build vendor intelligence
- Build promotion reporting
- Add procurement planning views
- Add inventory alerts
- Add notification management
- Build compliance monitoring summaries

Completion criteria:

- Modules use consistent data structures
- Alerts are explainable
- User permissions are enforced
- Important actions are recorded

### 37.5 Phase 4 — Backend and Security Foundation

Objectives:

- Establish the production-oriented database structure
- Implement authentication
- Implement role-based permissions
- Enforce organization data isolation
- Establish secure backend operations
- Add audit logging
- Implement backup and recovery procedures

Completion criteria:

- Authentication works reliably
- Organization isolation is tested
- Unauthorized access is blocked
- Sensitive information is protected
- Security testing is documented

### 37.6 Phase 5 — Authorized Integration Readiness

Objectives:

- Establish the integration framework
- Build simulated connector workflows
- Implement data validation
- Add duplicate detection
- Add synchronization monitoring
- Document provider authorization requirements

Completion criteria:

- Simulated imports work correctly
- Duplicate records are detected
- Failed synchronization is visible
- Source records remain traceable
- Integration permissions are enforced

Production integrations require separate authorization and validation.

### 37.7 Phase 6 — Controlled Pilot

Objectives:

- Prepare a controlled demonstration
- Validate the platform with appropriate authorized business participants
- Collect structured feedback
- Evaluate usability
- Review reporting accuracy
- Identify technical issues

Completion criteria:

- Critical issues are resolved
- Feedback is documented
- Security and reliability checks are completed
- Pilot approval requirements are satisfied

### 37.8 Phase 7 — Initial Product Release

Objectives:

- Prepare production infrastructure
- Complete release testing
- Finalize customer onboarding
- Establish support procedures
- Configure subscription management
- Publish product documentation

A production release must not occur until security, legal, technical, and operational readiness requirements are satisfied.

### 37.9 Phase 8 — Expansion

Future development may include:

- Advanced reporting
- Additional authorized integrations
- Expanded multi-location capabilities
- Supplier-facing experiences
- Mobile application support
- Advanced automation
- Additional state-specific configurations

### 37.10 Roadmap Management

The roadmap should remain flexible.

Each development phase should have:

- Defined objectives
- Prioritized tasks
- Assigned responsibilities
- Estimated resources
- Dependencies
- Testing requirements
- Completion criteria
- Documented release decisions

Development should prioritize a reliable, secure, useful product over rapid feature expansion.

## 38. Customer Support and Success

### 38.1 Support Objectives

BlackGrid Cannabis OS should provide a reliable customer support experience that helps authorized users understand the platform, resolve technical issues, and use available features effectively.

### 38.2 Support Channels

The platform should eventually support:

- Customer support email
- In-app support requests
- Help center and documentation
- Frequently asked questions
- Product tutorials
- System status announcements

Additional support channels may be introduced as the company grows.

### 38.3 Support Request Management

The support system should allow customers to:

- Submit support requests
- Select an issue category
- Describe the problem
- Attach relevant permitted files
- Review request status
- Receive updates
- View resolution history

### 38.4 Support Priority

Support requests should be categorized by priority:

- Critical: major service interruption or significant security concern
- High: important functionality unavailable
- Medium: limited functionality or recurring technical issue
- Low: general question or feature guidance

Priority definitions and response expectations should be documented.

### 38.5 Help Center

The help center should provide organized documentation covering:

- Account setup
- Dashboard navigation
- User permissions
- Financial reports
- Inventory reporting
- Product profitability
- Notifications
- Integration configuration
- Account settings
- Troubleshooting

Documentation should be updated when major features change.

### 38.6 Customer Success

BlackGrid should help customers understand how to use the platform effectively through:

- Onboarding guidance
- Feature education
- Product updates
- Usage guidance
- Feedback collection
- Periodic account reviews where appropriate

### 38.7 Feedback Management

Customers should be able to submit:

- Feature requests
- Product suggestions
- Usability feedback
- Bug reports
- General comments

Feedback should be categorized and reviewed to help guide future development.

### 38.8 Support Security and Privacy

Support personnel should only access customer information when authorized and necessary.

The support process must:

- Protect confidential business information
- Avoid requesting passwords or authentication secrets
- Use secure file-handling procedures
- Record important administrative support actions
- Follow applicable privacy and data-retention policies

### 38.9 MVP Requirements

The initial MVP should include:

- Basic support contact information
- A simple support request form
- Issue categories
- Request status tracking
- Basic help documentation
- A feedback collection mechanism

Advanced customer success automation can be introduced in later releases.

## 39. Product Analytics and Usage Intelligence

### 39.1 Objectives

BlackGrid should use privacy-conscious product analytics to understand how customers interact with the platform and identify opportunities to improve usability, reliability, and customer satisfaction.

Product analytics must remain separate from customer business-performance analytics.

### 39.2 Platform Usage Metrics

The system should support tracking appropriate product usage information, including:

- Active organizations
- Active users
- Login activity
- Feature usage
- Dashboard engagement
- Report usage
- Notification engagement
- Onboarding completion
- Support request volume

### 39.3 Feature Adoption

BlackGrid should measure how customers adopt major application modules, including:

- Owner dashboard
- Financial intelligence
- Sales reporting
- Product profitability
- Inventory intelligence
- Vendor intelligence
- Promotions
- Reporting
- Notifications
- Integrations

These measurements should help prioritize product improvements.

### 39.4 Application Reliability Metrics

The platform should monitor:

- Application availability
- Page loading performance
- API response times
- Error rates
- Failed operations
- Synchronization failures
- Background processing failures
- Database performance

### 39.5 Customer Experience Metrics

The platform should support measurement of:

- Onboarding completion rates
- Support request trends
- Common usability issues
- Feature adoption
- Customer feedback
- Customer satisfaction where voluntarily provided

### 39.6 Privacy and Data Boundaries

Product analytics must follow data-minimization principles.

The system should:

- Collect only necessary usage information
- Avoid collecting sensitive personal information unnecessarily
- Restrict access to analytics
- Separate product analytics from customer business records
- Apply appropriate retention policies
- Document analytics collection practices

Customer business information must not be repurposed for unrelated product analytics without appropriate authorization.

### 39.7 Internal Product Dashboard

Authorized BlackGrid personnel should eventually have access to an internal product analytics dashboard showing:

- Platform usage trends
- Feature adoption
- Reliability indicators
- Error trends
- Onboarding performance
- Support trends

The dashboard must not expose customer information beyond authorized operational requirements.

### 39.8 MVP Requirements

The initial MVP should include:

- Basic application error monitoring
- Basic usage event tracking
- Feature adoption indicators
- Application performance monitoring
- Privacy-conscious analytics configuration

Advanced product analytics can be introduced after the initial application foundation is stable.

## 40. Brand Identity and Product Experience

### 40.1 Brand Identity

The company brand is **BlackGrid Innovations**.

The software product is **BlackGrid Cannabis OS**.

BlackGrid should communicate:

- Intelligence
- Reliability
- Innovation
- Professionalism
- Security
- Operational clarity
- Business confidence

The product should feel like a premium enterprise software platform rather than a generic industry dashboard.

### 40.2 Visual Design Direction

The platform should use a hybrid interface:

- Dark navigation and sidebar
- Clean, light main workspace
- Structured information hierarchy
- Modern typography
- Consistent spacing
- Clear data visualizations
- Professional dashboard layouts

### 40.3 Color System

The primary visual system should include:

**Dark charcoal and black**
Used for navigation, primary interface framing, and brand identity.

**Electric green**
Used for positive performance, growth, savings, and successful actions.

**Red**
Used for critical alerts, important warnings, financial losses, and declining performance.

**Amber and orange**
Used for caution indicators and items requiring review.

**Neutral gray**
Used for informational content, secondary labels, and supporting interface elements.

Color must never be the only way important information is communicated. Labels, icons, and descriptive text should also identify status.

### 40.4 Logo and Brand Assets

BlackGrid should develop a consistent brand identity system that includes:

- Primary company logo
- Product logo
- Application icon
- Light-background logo variation
- Dark-background logo variation
- Brand color specifications
- Typography guidelines

Brand assets should be reusable across the application, website, documentation, and future marketing materials.

### 40.5 User Experience Principles

The application should prioritize:

- Clarity over unnecessary complexity
- Useful information over decorative elements
- Consistent navigation
- Fast access to important insights
- Clear explanations of financial metrics
- Understandable alerts
- Accessible interface components
- Responsive layouts

### 40.6 Role-Based Experience

The visual experience should adapt to each user's responsibilities while maintaining one connected platform.

**Owner**
Emphasize financial intelligence, business performance, profitability, and organization-wide visibility.

**Manager**
Emphasize operational reporting, inventory visibility, assigned responsibilities, and location-level information.

**Employee**
Emphasize permitted tasks, relevant notifications, and limited operational information.

**Administrator**
Emphasize system configuration, account management, integrations, security, and audit history.

### 40.7 Dashboard Standards

Dashboards should use consistent patterns for:

- Metric cards
- Trend charts
- Tables
- Filters
- Status indicators
- Notifications
- Supporting explanations
- Navigation

Important information should be easy to identify without overwhelming the user.

### 40.8 Accessibility

The interface should follow recognized accessibility practices, including:

- Readable text
- Sufficient contrast
- Keyboard navigation
- Accessible form labels
- Clear focus indicators
- Descriptive icons
- Screen-reader-friendly components
- Responsive layouts

### 40.9 Product Consistency

All application modules should follow the same design system.

New features should reuse established components and patterns wherever practical.

### 40.10 MVP Requirements

The initial MVP should include:

- Consistent BlackGrid branding
- Dark navigation and light workspace
- Defined color system
- Reusable interface components
- Role-specific dashboard layouts
- Responsive design
- Consistent typography and spacing
- Accessible status indicators

## 41. Website and Public-Facing Digital Presence

### 41.1 Website Objectives

BlackGrid Innovations should have a professional public-facing website that introduces the company, explains BlackGrid Cannabis OS, and provides a clear way for prospective business customers to request information.

The website should communicate credibility, innovation, security, and product value.

### 41.2 Primary Website Pages

The website should eventually include:

- Home
- About BlackGrid
- Product Overview
- Platform Features
- Security and Privacy
- Company Contact
- Request a Demonstration
- Customer Support
- Privacy Policy
- Terms of Service

### 41.3 Homepage

The homepage should introduce BlackGrid Innovations and clearly explain the purpose of BlackGrid Cannabis OS.

It should include:

- Company branding
- Product introduction
- Core platform capabilities
- Key product benefits
- Product interface previews
- Security and reliability messaging
- Demonstration request link
- Contact information

### 41.4 Product Overview

The product page should explain the platform's major capabilities:

- Financial intelligence
- Sales reporting
- Product profitability
- Inventory intelligence
- Vendor intelligence
- Promotion reporting
- Compliance monitoring
- Business analytics
- Multi-location visibility
- Authorized integrations

Product descriptions must accurately reflect features that have actually been implemented.

### 41.5 Demonstration Requests

Prospective business customers should be able to submit a demonstration request through a secure form.

The form should collect only necessary business contact information.

Requests should be stored securely and made accessible only to authorized personnel.

### 41.6 Brand Consistency

The public website should follow the BlackGrid visual identity:

- Dark charcoal and black
- Electric green accents
- Clean typography
- Modern layouts
- Professional product imagery
- Consistent company and product branding

### 41.7 Website Security

The website should support:

- HTTPS
- Secure form handling
- Spam protection
- Privacy-conscious analytics
- Secure administrative access
- Appropriate data retention
- Accessible design

### 41.8 Search and Discoverability

The website should use clear page titles, descriptions, structured content, and accessible navigation.

Search optimization should focus on accurately describing the software platform and its capabilities.

### 41.9 MVP Requirements

The initial public website should include:

- Homepage
- Company introduction
- Product overview
- Feature descriptions
- Contact information
- Demonstration request form
- Privacy policy
- Terms of service

The website must not advertise capabilities that are not yet available.

## 42. Legal, Regulatory, and Business Governance

### 42.1 Governance Objectives

BlackGrid Innovations should operate with documented business policies, appropriate legal protections, and responsible software development practices.

The platform must be designed to support authorized business customers without replacing their legal, regulatory, or professional responsibilities.

### 42.2 Company Documentation

BlackGrid Innovations should establish and maintain appropriate company documentation, including:

- Company formation records
- Ownership documentation
- Business agreements
- Intellectual property records
- Vendor agreements
- Customer agreements
- Internal operating policies

### 42.3 Customer Agreements

The company should establish appropriate customer agreements covering:

- Software subscription terms
- Permitted platform use
- Customer responsibilities
- Data ownership
- Privacy obligations
- Security responsibilities
- Service availability
- Support expectations
- Subscription cancellation
- Limitation of liability
- Dispute resolution

Final agreements should be reviewed by qualified legal counsel.

### 42.4 Privacy and Data Protection

BlackGrid should maintain documented privacy and data protection policies.

These policies should address:

- Information collected
- Reasons for collection
- Data access
- Data retention
- Data sharing
- Customer data ownership
- Security safeguards
- Customer privacy requests
- Data deletion procedures

Applicable privacy requirements must be evaluated as the company and customer base expand.

### 42.5 Regulated-Industry Boundaries

BlackGrid is a software platform, not a substitute for a customer's required licenses, regulatory systems, legal advice, or professional compliance responsibilities.

The platform should:

- Support authorized business reporting
- Maintain accurate data records
- Provide transparent monitoring tools
- Identify potential data discrepancies
- Preserve relevant audit history
- Respect official provider and regulatory integration requirements

BlackGrid must not represent itself as a regulator or guarantee that a customer is compliant.

### 42.6 Regulatory Configuration

The architecture should support configurable jurisdiction-specific requirements.

Regulatory configurations must be reviewed and maintained using reliable, authorized information sources.

Changes should be documented, versioned, and auditable.

### 42.7 Intellectual Property

BlackGrid Innovations should maintain records relating to:

- Company branding
- Product names
- Software source code
- Original designs
- Documentation
- Proprietary business logic
- Third-party software licenses

The company should review intellectual property ownership and licensing arrangements before commercial release.

### 42.8 Third-Party Services

Third-party providers should be evaluated for:

- Security practices
- Privacy policies
- Reliability
- Contractual responsibilities
- Data processing practices
- Integration authorization
- Ongoing service availability

### 42.9 Internal Governance

The company should establish policies for:

- Administrative access
- Employee and contractor permissions
- Confidential information
- Software development practices
- Security incident handling
- Change management
- Customer support
- Record retention

### 42.10 MVP Requirements

Before introducing real customer data or commercial production use, BlackGrid should complete appropriate reviews of:

- Company and contractual documentation
- Privacy and data handling
- Security controls
- Third-party service agreements
- Intellectual property
- Applicable industry requirements

Legal and regulatory decisions must be reviewed with qualified professionals.
