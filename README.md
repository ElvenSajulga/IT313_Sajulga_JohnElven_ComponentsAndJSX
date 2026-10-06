# IT313 Laboratory 4 - Components and JSX

## Problem

This project is a student roster made with React Native and Expo. It displays each student using a reusable StudentCard component. Each card shows the student's name, course, and units. The Full Load label only appears when the student's isFullLoad value is true.

## Component Structure

### StudentCard

StudentCard is a functional component that receives name, course, units, and isFullLoad as props. It uses destructuring and JSX expressions to display the student's information.

### StudentRoster

StudentRoster is the parent component that contains the student data. It uses .map() to create one StudentCard for each student and uses the student's ID as the key.

## How to Run

Run the following command in the project terminal:

npx expo start