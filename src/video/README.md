# Video Module

This module handles all video-based processing for the Truth-Seeker system.

## Responsibilities
- Load input video files
- Extract frames at fixed intervals
- Perform basic preprocessing on frames
- Prepare visual features for deepfake detection

## Planned Files
- frame_extraction.py : Extract frames from video files
- face_detection.py  : Detect and crop facial regions (optional)
- feature_extractor.py : Extract visual features using CNN models

## Output
Processed video frames or visual feature vectors that are passed to the
multimodal fusion module.
