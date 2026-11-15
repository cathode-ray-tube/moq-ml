# moq-moderate

A machine-learning content moderation pipeline for Media-over-QUIC (MoQ) streams.

`moq-moderate` analyzes live media for potentially unsuitable content, based on the models and moderation criteria configured by an application. It publishes timestamped moderation signals on a MoQ track to support downstream review or policy enforcement.

Model outputs are signals for applications to interpret—not definitive judgments about content.

## Status

Early-stage project. Interfaces, formats, and implementation details are subject to change.
