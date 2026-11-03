![](screenshot.png)

SpeedMeter is a versatile Kivy widget aimed at representing numerical
‘physical’ values in a “clock-face” or dial manner.

Minimum and maximum value, and the start and end angle, notably, are
fully configurable. For the sake of readability, the “labels”
(intermediate values represented on the dial) are integers, but you
can override the display function to represent whatever string fits
your needs, as illustrated with PI fractions in demo1.

SpeedMeter is clickable, so you can click on it, and the widget is
able to compute the corresponding physical value.

All default values are “reasonable”, so if you do nothing, you get a
working widget for the range 0..100 (asymmetric, because I think it’s
cool).

For now, SpeedMeter has been tested under Linux and Android (with
buildozer).

Speedmeter functionalities were heavily inspired by Andrea Gavana’s
SpeedMeter for wxPython.

The documentation is at https://kivy-garden.github.io/speedmeter/

## Repository status and workstream maintenance

Documentation review: 3 November 2026. This is repository-local status, not an upstream release or deployment acceptance.

### Purpose and function

Kivy dial-style widget for displaying configurable numerical measurements.

### Current objective

Maintain a clearly documented local copy for authorised evaluation/development, preserving upstream attribution and distinguishing local changes from upstream capabilities.

### Progress and evidence

This is a fork of kivy-garden/speedmeter. Existing upstream documentation and attribution are retained. Local customisation, upstream parity, build success and runtime/hardware acceptance have not been verified in this documentation review.

### Next steps and roadmap

1. Confirm the next owner-approved outcome and reconcile this default branch with the workstream's actual source, test evidence and deployed version.
2. Compare with the upstream project before updating and use an appropriate disposable/non-live test setup.
3. Keep completed/in-progress/blocked work and next actions current here. Broader feature priorities remain for the owning workstream to agree; this update does not invent a feature commitment.

### Documentation chain

Read this README first, then the existing records and source/example entry points below. Listed paths were observed on the inspected default branch; source folders are not test results.

- [doc](doc)

- [Upstream repository](https://github.com/kivy-garden/speedmeter)

### Standing instruction for every workstream

Every agent, developer or project workstream maintaining this repository must automatically keep this README current with its purpose/function, agreed objective, dated progress, blockers, roadmap/next actions and links to authoritative records. Update it when these facts materially change, at meaningful milestones and before handback, interruption or completion; do not wait for a separate owner reminder.

Read applicable project instructions, preserve concurrent work and existing attribution/licences, and distinguish source commits from deployed versions and verified results. Link requirements, design, handover, validation and recovery records when they exist rather than creating conflicting copies. If a fact is unknown, say so and identify the next verification action. Check affected links, publish authorised changes and verify the remote commit before claiming completion.

Keep credentials, private infrastructure/access routes, private datasets and confidential material out of public documentation. This instruction does not grant new access, replace project-specific authority or approve untested hardware/live operations. Retain detailed historical evidence in project records/version history rather than an ever-growing README log.
