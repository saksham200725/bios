
# HandTrace Event Data Format

This document describes the example event format used in HandTrace.

## Fields

- `clip_id`: Identifier for the sample video.
- `event_id`: Unique identifier for an event.
- `start_sec`: Event start time in seconds.
- `end_sec`: Event end time in seconds.
- `action`: Label for the observed hand action.
- `hand_side`: Left or right hand.
- `object_label`: Label for the object, if known.
- `contact_state`: Estimated contact state.
- `tracking_quality`: Tracking quality score, if provided by the tracking module.
- `review_status`: Whether the event is pending review or has been reviewed.

## Important

This is an example format. Confirm the final field names and meanings with the team before integrating their outputs.
