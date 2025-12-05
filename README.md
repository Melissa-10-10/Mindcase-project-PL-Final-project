# Mindcase-project-PL-Final-project

# MindEase – Smart Mental Health Support and
Tracking System

## INTRODUTION

MindEase is a smart mental health support and tracking system that helps users monitor and
manage their emotional well-being. The platform allows users to log their moods, perform quick
self-assessments, and receive tailored recommendations to improve their mental health. It uses
data analysis to identify mood patterns and provide timely advice or professional guidance. This
system encourages early mental health awareness and self-care.

'''sql

CREATE OR REPLACE FUNCTION IS_ACTION_ALLOWED (
    p_action_date IN DATE -- Parameter not used in simulation
)
RETURN BOOLEAN
AS
BEGIN
    -- *** SIMULATION MODE: FORCING WEEKEND ACCESS ALLOWED ***
    RETURN TRUE; 
END IS_ACTION_ALLOWED;
/
'''
