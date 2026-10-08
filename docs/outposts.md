# Global-map outposts: sending workers and collecting resources

Outposts can be constructed at captured global-map locations, including
resource-producing locations. They are **not established by a combat-only raid**.

## Official steps

According to a developer response on June 30, 2023:

1. Build a **resource collection station** (terminology used in the response).
2. Put **at least one soldier inside a truck**. To board a vehicle, select
   the soldier and **right-click the vehicle**. This control is explicitly
   described in the official August 2022 update.
3. Ensure you have enough **available workers** in your settlement. Each
   outpost location requires a different number of workers.
4. In the **raid-creation window**, create a group containing the **vehicle
   and workers**.
5. Send the group **directly to the possible resource-construction point**
   on the global map.
6. Wait: both outpost construction and resource extraction take game time.
7. When extraction is complete, the vehicle squad reappears on the global
   map carrying the resources.
8. Order it back to the settlement and park the vehicle **near the resource
   unloading station** to deliver its cargo.

The developer also states that workers only need to accompany the convoy
for the **initial outpost construction** phase; they do not need to be
included in every later resource-collection trip.

Sources:

- [Developer explanation in Steam gameplay discussion, June 30, 2023](https://steamcommunity.com/app/1203930/discussions/0/3805027459316174103/)
- [Official v2.08.01 announcement introducing outposts and worker/vehicle convoys](https://steamdb.info/patchnotes/9228031/)

## Repair & Service Point versus expedition creation

The Repair & Service Point's **Available Blueprints** screen is for vehicle
production, not worker assignment or expedition orders. In a submitted
screenshot it displayed:

- **4/4** workers assigned to the Repair & Service Point
- **Vehicles** blueprint at **200 metal** and **180 in-game hours**
- **0** owned units shown beside several vehicle blueprint icons

The player should close this production panel, board an owned drivable
truck/van with a soldier via right-click, and then prepare the expedition
from Headquarters. Vehicles visible parked nearby are not proof that they
are currently available to Headquarters; check that a soldier has boarded.
An older player report specifically notes Headquarters not recognizing a
vehicle until a soldier is in the driver's seat.

Sources:

- [Official v2.08.01 notes: boarding soldiers by right-clicking transport](https://steamdb.info/patchnotes/9228031/)
- [Player report about vehicle recognition and outpost convoys](https://steamcommunity.com/app/1203930/discussions/0/3806156528951277547/)

## Player observation: construction point with 0/5 workers

A global-map marker displayed:

- **Place for Construction**
- **Workers: 0 / 5**
- **Resources: Wood (0)**

This suggests a construction point with capacity/requirement for five workers,
but the exact meaning of the progress counter should be verified during a
working expedition. Check the number of **available workers**, the **soldier
physically seated in the vehicle**, and whether the vehicle is included in
the raid-creation group.

## Troubleshooting

- **Raid cannot be sent into the construction point:** ensure this is a
  *captured* location and that the group includes a vehicle with at least
  one soldier seated, plus available workers.
- **0/5 doesn't change:** recheck the workers included in raid creation,
  rather than merely the soldiers assigned to a normal raid.
- **Squad returns without delivering goods:** use the unloading station.
- **Outpost/convey seems stuck or duplicates:** developers fixed some
  outpost construction, map interaction, and duplicate-unit bugs in a later
  patch. Save before retrying.

These steps come from a developer explanation published in 2023. Exact
buttons and bug behavior should be checked against the current v5.09.13 UI.

Related patch:
[October 2023 outpost fixes](https://steamdb.info/patchnotes/11882933/).
