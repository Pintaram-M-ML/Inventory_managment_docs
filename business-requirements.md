Inventory Management System - Business Requirements Document 

Summary 

Inventory Management System is an open-source solution designed to help small to medium businesses manage their parts and stock easily. The system works on computers, tablets, and phones.  

Business Requirements 

Core Business Capabilities 

Inventory Management System helps businesses track their physical inventory, manage production processes, and maintain relationships with suppliers and customers throughout the product lifecycle.

Parts Management 

The parts management feature is the foundation of the Inventory Management System. Organizations can create and maintain detailed records for every component, assembly, and finished product in their inventory. Each part can be organized into categories that reflect how the business operates. Parts include information like part numbers, descriptions, version history, and custom details. The system handles different part types including parts that are purchased, parts that are made from other parts, and virtual parts that represent services. 

Parts can be linked to multiple suppliers, helping businesses track different sources and pricing information. Each part maintains a list of components needed for assembly. The system tracks part versions to keep historical records of design changes. Custom fields can be added to parts to capture specific information unique to your industry or business.

Stock Control and Tracking 

Stock control provides real-time visibility into inventory levels across all storage locations. Stock items can be tracked individually through serial numbers or managed in bulk quantities. The system maintains a complete history of all stock movements and changes for full tracking and record-keeping. 

Stock locations are organized in a structure that mirrors your physical warehouse layout, allowing businesses to define buildings, rooms, aisles, shelves, and bins as needed. Each stock item is assigned to a specific location, and the system tracks all movements between locations. Stock can be transferred, counted, added, or removed with complete logging. The system supports expiry date tracking for time-sensitive materials and components. 

Stock ownership features allow businesses to track items that belong to customers or are provided by suppliers. Stock status labels provide flexibility to mark items as available, quarantined, damaged, or in other custom states. The system generates automatic alerts when stock levels fall below defined thresholds, enabling proactive reordering.

Manufacturing and Build Management 

The manufacturing module helps businesses plan and execute production activities. Build orders represent the process of creating new parts from existing stock by following a list of required components. The system tracks build progress through multiple stages from planning through completion. 

Build orders use stock items according to the component list, with support for both automatic and manual selection of components. The system can select stock from specific locations or allow flexible selection based on availability. Build outputs represent the finished products created by the build process, which can be tracked individually or created in bulk quantities. 

The system supports scenarios where build orders are sent to external manufacturers. Build orders can be linked to customer orders to support make-to-order production. Test results can be recorded for finished products to document quality control and testing activities.

Purchasing and Supplier Management 

The purchasing module manages the buying process from supplier selection through receiving goods. Supplier companies are maintained in the system with contact information, payment terms, and performance history. Supplier parts link your internal parts to specific supplier catalog numbers and pricing information. 

Purchase orders formalize the buying process with line items, quantities, pricing, and delivery schedules. The system tracks purchase order status through stages including pending, placed, received, and completed. Partial receipts are supported, allowing businesses to receive portions of an order as they arrive. Received items are automatically added to stock at specified locations. 

Supplier volume pricing enables pricing structures where unit costs decrease at defined quantity levels. The system can track multiple suppliers for each part, supporting competitive sourcing and supply chain options. Purchase order history provides visibility into past buying activities and spending patterns.

Sales and Customer Management 

The sales module manages customer relationships and order fulfillment. Customer companies are maintained with shipping addresses, payment terms, and order history. Sales orders capture customer requirements with line items, quantities, pricing, and delivery commitments. 

Sales order allocation links specific stock items to customer orders, reserving inventory for fulfillment. The system supports partial allocations and backorders when stock is not enough to fulfill the complete order. Shipments group allocated items for delivery, with tracking numbers and shipping dates recorded. 

Return orders handle the process when customers return products. The system tracks return reasons, decisions, and restocking activities. Sales order history provides complete visibility into customer purchasing patterns and fulfillment performance.

Reporting and Documentation 

The reporting system generates customized documents using templates. Report templates can be created for purchase orders, sales orders, build orders, packing lists, and other business documents. Label templates support barcode labels, part labels, location labels, and other identification needs. 

Templates are created using standard web formats with access to data from the system database. The system provides data fields and helper functions to simplify template creation. Reports can be generated in PDF format for printing or electronic distribution. The template system supports conditional logic, loops, and formatting to create sophisticated documents.

Barcode Integration 

Barcode capabilities streamline data entry and improve accuracy throughout the system. The system supports internal barcode formats for parts, stock items, and locations. External barcode formats from suppliers like DigiKey, Mouser, LCSC, and TME can be scanned and automatically matched to parts and purchase orders. 

Barcode scanning is integrated into receiving workflows, stock movements, build allocation, and sales order picking. The system maintains a history of all barcode scans for record-keeping purposes. Custom barcode extensions can be developed to support additional barcode formats and integration scenarios.

User Management and Security 

User management provides role-based access control to secure sensitive data and operations. User accounts can be assigned to groups that define permissions for viewing, creating, modifying, and deleting different types of data. The system supports single sign-on integration with external identity providers. 

Multi-factor authentication adds an additional security layer for user logins. Email notifications keep users informed of important events and required actions. The system tracks user activity for record-keeping and compliance purposes. User preferences allow customization of language, theme, and interface settings.

Extension System and Customization 

The system provides an extension system that allows businesses to add custom functionality without modifying the core application. Extensions can integrate with various aspects of the system including barcode scanning, event handling, data export, label printing, notifications, currency exchange, and supplier integration. 

The extension system allows extensions to provide specific functionality. Action extensions add custom operations to the user interface. Connection extensions expose custom endpoints for external integrations. Barcode extensions decode proprietary barcode formats. Event extensions respond to system events like part creation or stock movements. Label printing extensions integrate with physical label printers and printing services. 

Notification extensions deliver alerts through channels like email, Slack, and in-application messages. Currency exchange extensions provide real-time exchange rates for multi-currency pricing. Schedule extensions execute recurring tasks on defined intervals. Validation extensions enforce custom business rules and data quality checks. The extension system supports configuration settings, background task execution, and database access.

