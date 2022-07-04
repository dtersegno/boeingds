Boeing data science challenge problem
---

Instructions [here](./Boeing%20Data%20Science%20Challenge%20Problem%20Instructions.pdf).


| Parameter | Type |  Description|
| --- | --- | --- |
| ListingID  | int64  | Unique key that identifies each listing| 
|SellerCity |object |Seller city|
|SellerIsPriv bool Boolean that indicates if the listing if from a private seller
|SellerListSrc object Seller listing source identifier
|SellerName object Seller name
|SellerRating float64 Seller rating (continuous over [0,5] with 5 being a favorable rating)
|SellerRevCnt int64 Seller review count
|SellerState object Seller state
|SellerZip float64 Seller zip code
|VehCertified bool
|Boolean that indicates if the listing has a manufacturer certification
|(generally indicates extended warranty)
|VehColorExt object Vehicle exterior color
|VehColorInt object Vehicle interior color
|VehDriveTrain object Vehicle drivetrain (rear/front/all wheel drive)
|VehEngine object
|Vehicle engine (generally includes displacement size, whether it is
|turbocharged, sometimes includes fuel type)
|VehFeats object Vehicle features as listed by the seller in a semi-structured list format
|VehFuel object Vehicle fuel type
|VehHistory object
|Vehicle ownership history in a semi-structured format that may also
|indicate if there is buy-back protection, previous commercial use,
|accidents, or potential title problems
|VehListdays float64 Duration (in days) the vehicle listing has been active
|VehMake object Vehicle make (manufacturer)
|VehMileage float64 Vehicle mileage
|VehModel object Vehicle model
|VehPriceLabel object
|A classification label applied by the listing site that indicates if the
|listing price is a good deal or not
|VehSellerNotes object
|Unstructured text the seller has entered that provides additional
|details on the vehicle
|VehSellerStockNum object Vehicle seller stock number
|VehTransmission object Vehicle transmission type
|VehYear int64 Vehicle model year (not necessarily the year it was manufactured)
|Vehicle_Trim object Vehicle trim
|Dealer_Listing_Price float64 Vehicle listing price, dependent variable to be predicted.
