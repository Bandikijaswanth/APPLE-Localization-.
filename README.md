# APPLE-Localization-.
AIM

To evaluate localization accuracy by comparing pose error with a predefined threshold.

PROCEDURE
Initialize the pose error value
Define an acceptable error threshold
Compare pose error with the threshold
If error < threshold, confirm accurate localization
Otherwise, mark as inaccurate
Display the result
CODE
# Pose error
pose_error = 0.08   # in meters

# Threshold
threshold = 0.1

# Localization accuracy check
if pose_error < threshold:
    result = "Accurate Localization"
else:
    result = "Localization Error High"

# Output
print(result)
OUTPUT

Accurate Localization

RESULT

The localization system is accurate since the pose error is within the acceptable threshold.
