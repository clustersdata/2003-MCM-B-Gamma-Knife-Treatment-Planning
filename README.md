# 2003-MCM-B-Gamma-Knife-Treatment-Planning


Stereotactic radiosurgery delivers a single high dose of ionizing radiation to a radiographically well-defined, small intracranial 3D brain tumor without delivering any significant fraction of the prescribed dose to the surrounding brain tissue. Three modalities are commonly used in this area; they are the gamma knife unit, heavy charged particle beams, and external high-energy photon beams from linear accelerators.

The gamma knife unit delivers a single high dose of ionizing radiation emanating from 201 cobalt-60 unit sources through a heavy helmet. All 201 beams simultaneously intersect at the isocenter, resulting in a spherical (approximately) dose distribution at the effective dose levels. Irradiating the isocenter to deliver dose is termed a “shot.” Shots can be represented as different spheres. Four interchangeable outer collimator helmets with beam channel diameters of 4, 8, 14, and 18 mm are available for irradiating different size volumes. For a target volume larger than one shot, multiple shots can be used to cover the entire target. In practice, most target volumes are treated with 1 to 15 shots. The target volume is a bounded, three-dimensional digital image that usually consists of millions of points.

The goal of radiosurgery is to deplete tumor cells while preserving normal structures. Since there are physical limitations and biological uncertainties involved in this therapy process, a treatment plan needs to account for all those limitations and uncertainties. In general, an optimal treatment plan is designed to meet the following requirements.

    Minimize the dose gradient across the target volume.
    Match specified isodose contours to the target volumes.
    Match specified dose-volume constraints of the target and critical organ.
    Minimize the integral dose to the entire volume of normal tissues or organs.
    Constrain dose to specified normal tissue points below tolerance doses.
    Minimize the maximum dose to critical volumes.

In gamma unit treatment planning, we have the following constraints:

    Prohibit shots from protruding outside the target.
    Prohibit shots from overlapping (to avoid hot spots).
    Cover the target volume with effective dosage as much as possible. But at least 90% of the target volume must be covered by shots.
    Use as few shots as possible.

Your tasks are to formulate the optimal treatment planning for a gamma knife unit as a sphere-packing problem, and propose an algorithm to find a solution. While designing your algorithm, you must keep in mind that your algorithm must be reasonably efficient.
