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
