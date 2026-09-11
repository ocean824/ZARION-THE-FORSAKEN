# ZARION — Production Systems

Domains: input, combat simulation, move/frame data, weapons/stances, style/ranking, enemies, bosses, missions, camera, animation, VFX/audio, UI, save/replay.

Moves have stable IDs and authored startup/active/recovery/cancel/hit properties. Combat instrumentation records input/action/hit/style events. Enemy attack coordination enforces fairness/off-camera policy. Difficulty can change behavior/composition/timing with explicit data.

Requirements: ZAR-REQ-001 responsive combat; 002 inspectable frame/cancel rules; 003 style expression; 004 enemy fairness; 005 boss phase integrity; 006 60+ FPS target profile; 007 Unreal/AXIOM golden combat parity.
