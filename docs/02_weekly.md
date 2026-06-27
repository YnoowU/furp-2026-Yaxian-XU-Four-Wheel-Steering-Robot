# Weekly Progress Log

Week 2 — 2026-06-27
Attended this week's meeting: Yes

Progress this week

Built a basic steering wheel (swerve drive) chassis physical model in MATLAB Simscape Multibody, including 4 steering wheel modules, 1 chassis body, and proper ground contact force configurations.

Successfully implemented and debugged the motion control pipeline: by inputting target linear velocities (vx, vy) and angular velocity (Omega), the model correctly resolves the kinematics to drive the 4 steering wheels, allowing the chassis to execute commands as expected.

Challenges & blockers

Tuning contact force parameters: Spent some time fine-tuning the contact stiffness and damping coefficients to ensure the 4 wheels maintain stable ground contact without realistic slipping or high-frequency jittering.

Next steps

Further optimize control responses and test chassis stability under dynamic velocity commands or uneven terrain.

Revisit last week's goal regarding robot modeling—explore syncing or importing more detailed asset formats (like USD) into MATLAB or MuJoCo alongside this working control loop.

Week 1 — 2026-06-20
Attended this week's meeting: Yes

Progress this week

Learned the fundamentals of MATLAB Simscape Multibody and understood the functions of various blocks for multi-body simulation.

Studied the kinematic forward/inverse resolution (解算) for steering wheel (舵轮) chassis configurations.

Learned the basics of ROS 2 based on the provided documentation and successfully ran some simple introductory code.

Installed the MuJoCo simulator and started exploring scene modeling and simulation.

Challenges & blockers

Still exploring how Universal Scene Description (.usd) files work and how to complete the robot modeling process.

Currently uncertain about the pipeline to import and animate USD files properly within the MATLAB environment.

Next steps

Continue researching how to successfully bring the robot model and control loops into the simulation environments (MATLAB/MuJoCo).

Wait for and review the overview/general structure of the project in MATLAB to align my next development steps.

> Update this file **every week**. Add a new entry at the top for each week.
> This is the first thing we check during review. Keep it honest and specific — it also feeds your attendance record (Rule 1).

**How to use:** copy the *Week template* block below for each new week. Newest week goes at the top.

---

## Week template — copy me

### Week N — YYYY-MM-DD

**Attended this week's meeting:** Yes / No (if No, did you email leave? Yes / No)

**Progress this week**
- _What did you actually do / finish?_

**Challenges & blockers**
- _What got in the way? What are you stuck on?_

**Next steps**
- _What will you do next week?_

**Hours spent (optional):** _e.g. 6h_

**Links (optional):** _commits, notebooks, docs, datasets..._

---

<!-- =================  YOUR ENTRIES BELOW  ================= -->

### Week 1 — YYYY-MM-DD

**Attended this week's meeting:** Yes / No

**Progress this week**
- Set up repository from the FURP template.
- _..._

**Challenges & blockers**
- _..._

**Next steps**
- _..._

**Hours spent (optional):**

**Links (optional):**
