# moq-ml

Machine-learning pipelines for Media over QUIC (MoQ) streams.

`moq-ml` processes live media from MoQ streams and publishes useful results alongside the source stream. Initial components:

- **`moq-transcribe`** — transcribes spoken audio and publishes timestamped transcription results.
- **`moq-moderate`** — uses machine-learning models to identify potentially unsuitable content in live media, such as material that may violate a community’s moderation rules.

## Pipeline

```text
MoQ media track → processing pipeline → ML inference → MoQ result track
```

Pipelines consume media tracks, run the relevant processing and inference, then publish results that applications can use alongside the original media.

## Status

Early-stage project. Interfaces, formats, and implementation details are subject to change.

## License

This project is dual-licensed: MIT OR Apache-2.0, choose either. See LICENSE-MIT and LICENSE-APACHE-2.0 in the repository root.

![moq-ml-logo](https://github.com/cathode-ray-tube/moq-ml/blob/main/assets/moq-ml-logo.jpeg))
