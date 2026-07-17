# Accepted exact-SIF registry

This independent DataLad dataset stores only exact SIF bytes that have reached
the `accepted-registered` image state. Its DataLad Containers configuration and
the corresponding root image record identify an image; a filename, source tag,
or Pixi lock does not.

The Phase 2 `toy-bids-app` SIF is a redistributable BIDS App interface fixture.
It validates registration, retrieval, annex-key lookup, and byte verification.
It is not a scientific runtime, and any output it produces is non-authoritative.

Candidate and rejected images never enter this dataset. A scientific candidate
must complete its own interface, containment, architecture, licensing,
retrieval, and hardening review before registration. The project records each
accepted image in `../../images/<image-id>.yaml`; the root image index is a
derived convenience view only.
