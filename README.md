# 5x5 Training Plan Generator

An automatic 5x5 strength training plan generator with progressive loading and deload weeks. This web application creates a complete 6-week training program plus a deload week based on your starting weights.

## Features

- **Automatic Training Plan Generation**: Calculates a complete 6-week progressive training plan plus a 7th deload week
- **Three Workout Split**: Organized into 3 distinct workouts targeting different muscle groups
- **Progressive Loading**: Automatically increases weights week by week with proper progression
- **Current Week Tracking**: Shows which week you're currently in based on your start date
- **1RM Calculator**: Built-in one-rep max calculator using the Brzycki formula
- **Responsive Design**: Clean, modern interface that works on desktop and mobile

## Workout Structure

### Workout 1 (Upper Body Focus)
- A1. Bench Press (5x5)
- B1. Pull-ups / Lat Pulldown (4 x 6-10)
- B2. Triceps Extensions (4 x 8-12)
- C1. Dips (4 x 10-15)
- C2. Bent Over Dumbbell Row (4 x 10-15)

### Workout 2 (Lower Body Focus)
- A1. Squat (5x5)
- B1. Dumbbell Reverse Lunge (4 x 16-24)
- B2. Hanging Leg Raise (4 x 15-20)
- C1. Dumbbell Romanian Deadlift (4 x 10-15)
- C2. Goblet Cyclist Squats (4 x 15-20)

### Workout 3 (Full Body Focus)
- A1. Deadlift (5x5)
- B1. Seated Dumbbell Shoulder Press (4 x 6-10)
- B2. Seated Bicep Curls (4 x 10-15)
- C1. Low Cable Fly Crossover (4 x 10-15)
- C2. Dumbbell Lateral Raise (4 x 10-15)

## How to Use

1. **Set Your Starting Weights**: Enter weights you can lift for 3-5 reps in the yellow input fields
2. **Set Start Date**: Choose when you want to begin the program
3. **Generate Plan**: Click "Calculate My Training Plan" to generate your complete program
4. **Track Progress**: The app automatically highlights your current week based on the start date

## Training Methodology

- **Main Lifts (5x5)**: Progressive pyramid sets with top set as your working weight
- **Accessory Exercises**: Fixed rep ranges with progressive weight increases
- **Progression**: 2.5kg increases per week for main lifts, 2.5% for accessories
- **Deload Week**: Week 7 reduces intensity to 60% for recovery

## Files

- `training5x5.html` - Complete training plan generator application
- `README.md` - This documentation

## Getting Started

Simply open `training5x5.html` in any modern web browser to start using the training plan generator. No installation or setup required.
