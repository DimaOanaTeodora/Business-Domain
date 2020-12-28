# Business Domain :money_with_wings: :chart:

Object Oriented Programming in C++

Company X has a business domain where it is necessary to follow the way in
which customers pay (cash, check or credit card). Regardless of the payment method, company X
he knows the date on which the payment was made and the amount received. If it is paid with the card, then
the credit card number is also known. For cash, it is not necessary to identify the customer
who made the payment.

Data structure: unordered_map or unordered_set <payment_id, the retaining structure payment dates>

Additional requirement:
- Add all relevant fields for modeling this problem.
- To build the Management template class containing the total number of payments of one
certain type (automatically incremented when a new receipt is added) and the object structure of
payment type, dynamically allocated. Load operator + = to insert a payment into
vector.
- To build a specialization related to the type of payment by card, to store and
number
of customers, along with their names. The specialization will adapt the operators mentioned in
requirements and the operator to this type of payment.
