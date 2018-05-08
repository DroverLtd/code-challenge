# **Drover Assignment - Insurance Calculator**

Drover is a vehicle rental market place where drivers can rent
a vehicle from an owner, Drover facilitates these rentals.

You should know this already!!

Drover needs to build a calculator to help them price their
2 new insurance products:

1. Driver Insurance
2. Vehicle Owner Insurance

You can read about these two products in the notes found in
their respective models.

Got it?? There are also some tests in the below files which
should help make more sense of this

- `spec/models/driver_insurance_spec.rb`
- `spec/models/vehicle_owner_insurance_spec.rb`

Drover brought in a new freelance developer to work on this
functionality.

Unfortunately this developer has written some dubious code and
mysteriously disappeared.

Note - The tests were written by us and you can assume are accurate.

We need the code to be fixed and completed, below is a summary of the remaining work.

**Please push the repo to your GitHub account and share the link
with us, DO NOT create a fork **

### Driver Insurance Spec

1. Make the test "calculates the number of days to charge for
   all the insurance for one driver" pass.
   You will need to complete the implementation of the method
   `total_days_charged_for_all_driver_insurance_policies`
   in `Partner`.
2. The third test passes but the functionality looks wrong,
   could you correct the problem here.
3. The code related to Driver Insurance (across all files) could do
   with refactoring.
   Please consider code simplicity, readability and maintainability
   when refactoring this code.
4. The fourth driver insurance test is only outlined and neither
   test code or functionality is in place, could you write both.

### Vehicle Owner Insurance Spec (optional - please leave if there is not time)

5. The second vehicle owner insurance spec passes but the
   functionality is clearly wrong. Could you fix the implementation.
6. We have recently been experimenting with a new pricing system for
   vehicle owner insurance, `version2` (described in the test).
   The third fleet insurance spec tests for this new pricing, but
   the functionality needs completing.
