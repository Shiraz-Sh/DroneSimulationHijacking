# Drone Simulation Hijacking

This project deals with the hijacking of a drone in a simulation environment using **PX4**.
The PDF of the project can be found in this repository.

---

## Dictionary Attack

The dictionary attack was done using the following files:

* `cracker.py`
* `dictionaryAttack.py`
* `words.py`

---

## Eavesdropping

The eavesdropping functionality is implemented in:

* `spy_drone.py`

---

## Signed Communication (Secure Version)

The code for the mock drone that uses signed communication can be found in:

* `mock_drone.py`

The code for sending signed messages (simulating the ground control in the signed version) can be found in:

* `inject_signed.py`

---

## Malicious Message Injection

The malicious message and the sending of it can be found in:

* `inject.py`
