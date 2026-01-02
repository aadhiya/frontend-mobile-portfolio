# frontend-mobile-portfolio
Frontend Portfolio
## 1. Redline – Car Service App (React Native/Expo)
**Live client app for garage staff: Job tracking, service management, billing & thermal printing.**

<div align="center">

### Dashboard & Services
**Login → Main Service List** (Client data – no live credentials available)
<img src="redline-carservice/login.jpeg" width="250"> <img src="redline-carservice/mainservice-list.jpeg" width="250"> ```

Job Cards Management
Assign services to employees with full vehicle details

<img src="redline-carservice/jobcard.jpeg" width="250">
<img src="redline-carservice/main-page.jpeg" width="250">

Quick Services & Estimates
Service catalog → Quick actions → Delivery scheduling → Estimates

Services List	Quick Service (Car Wash)	Delivery Date
<img src="redline-carservice/servicelist.jpeg" width="180">	<img src="redline-carservice/carwash.jpeg" width="180">	<img src="redline-carservice/deliverydate.jpeg" width="180">

Sub-Services	Vehicle Details	Estimate Approval
<img src="redline-carservice/select-service.jpeg" width="180">	<img src="redline-carservice/vehicle-detail.jpeg" width="180">	<img src="redline-carservice/estimate-page.jpeg" width="180">

Invoicing & Printing
Full service bills + Quick print for simple jobs

Main Service Bill	Quick Print Flow
<img src="redline-carservice/bill.jpeg" width="250">	

<img src="redline-carservice/quickprint(1).jpeg" width="180">
<img src="redline-carservice/quickprint(2).jpeg" width="180">
<img src="redline-carservice/quickbill.jpeg" width="180">
</div>
Supermarket Relevance: Service catalogs → product categories, job cards → orders, thermal printing → receipts, estimates → dynamic pricing.

Tech: Expo SDK 53, Material UI, responsive design. Production-ready for POS systems.


  ## 2. RentalApp – Flutter Inventory
**Client-specified simple, clean design for rental inventory management with stock tracking, billing, and thermal printing.**

### User Flow
1. **Browse & Select Items** – View available rentals with search and current stock levels.
2. **Enter Details** – Add customer info, select dates, capture photos (ID/vehicle).
3. **Generate Bill** – Calculate totals with discounts/advance, print receipt.
4. **View Reports** – Filter rentals by date/status (pending/paid).
5. **Manage Stock** – Add/update inventory items and quantities.

<div align="center">

  **Home Screen and available items screen**  
<img src="rentalappscreens/home.jpeg" width="250"> <img src="rentalappscreens/material-list.jpeg" width="250">

**Item Selection**  
<img src="rentalappscreens/select-item.jpeg" width="250"> <img src="rentalappscreens/select-date.jpeg" width="250">

**Customer Details**  
<img src="rentalappscreens/enter-customer-detail.jpeg" width="250"> <img src="rentalappscreens/addharpic.jpeg" width="250">

**Bill Generation**  
<img src="rentalappscreens/billscreen.jpeg" width="250">

**Rental Reports**  
<img src="rentalappscreens/reportscreen.jpeg" width="250">

**Stock Management**  
<img src="rentalappscreens/stockupdatescreen.jpeg" width="250">

</div>



**Supermarket Relevance:** Product catalog → available items list, receipt printing, inventory updates, sales reports by date.


## 3. DohaPride Driver – Taxi Dispatch App
**Real-time trips, maps, status updates.**

### Key Screens & Design Approach
- **Dashboard/Trips** : Map integration, real-time lists – delivery tracking.
  
[!trip](dohapride/home.jpeg)

- **Trip Details** : Status badges, car details – order status.
  
[!trip](dohapride/trip-detail.jpeg)
[!trip](dohapride/start-endoption.jpeg)
[!trip](dohapride/driver-detail.jpeg)
-
- **End Trip** : Image upload, confirmation – proof of delivery.
  
 [!trip]( dohapride/end-trip)

**Patterns for Supermarket:** Searchable lists, maps for stores, modals for quick actions.

## Relevance to Supermarket App
- **Inventory:** Job cards → Product lists with filters/images.
- **Checkout:** Service modals → Cart/add products.
- **Billing:** Thermal invoices → Receipts/POS printing.
- **UX:** Dark mode, responsive, intuitive for staff/clients.


