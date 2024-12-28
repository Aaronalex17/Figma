# Ex09 Event Registration Web Application
## Date:28/12/14

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
import React from 'react';
import './App.css';
import IPhone_16Pro_1 from './components/IPhone_16Pro_1';

function App() {
  return (
    <>
      <IPhone_16Pro_1 />
    </>
  );
}

export default App;
import React from 'react';
import styles from '../styles/IPhone_16Pro_1.module.css';


export default function IPhone_16Pro_1() {
  return (
    <div className={styles.IPhone_16Pro_1_8_20}>
      <div className={styles.Rectangle_1_1_6}></div><span className={styles.AnnualdayCelebration_1_8}>ANNUALDAY CELEBRATION </span><span className={styles.Register_1_7}>REGISTER</span>
      <div className={styles.Screenshot_2024_12_28_104656_1_31_2}></div>
      <div className={styles.Screenshot_2024_12_28_105536_1_31_6}></div>
      <div className={styles.Rectangle_11_31_7}></div><span className={styles.ChristmasCelebration_31_9}>christmas celebration</span>
    </div>
  );
}
@import "https://fonts.googleapis.com/css?family=Inter:0,undefined;0,900&display=swap";
.IPhone_16Pro_1_8_20 {
  background: #f3a4a4;
  width: 402px;
  height: 874px;
}
.Rectangle_1_1_6 {
  background: #ee0909;
  flex-shrink: 0;
  width: 290px;
  height: 73px;
}
.AnnualdayCelebration_1_8 {
  color: #000;
  flex-shrink: 0;
  width: 356px;
  height: 39px;
  font-family: Inter;
  font-size: 24px;
  font-style: normal;
  font-weight: 800;
  line-height: normal;
  display: inline-block;
}
.Register_1_7 {
  color: #fff;
  flex-shrink: 0;
  width: 321.201px;
  height: 60.045px;
  font-family: Inter;
  font-size: 40px;
  font-style: normal;
  font-weight: 800;
  line-height: normal;
  display: inline-block;
}
.Screenshot_2024_12_28_104656_1_31_2 {
  background: #d3d3d3 url(<path-to-image>) 50% / cover no-repeat;
  flex-shrink: 0;
  width: 389.833px;
  height: 115.604px;
}
.Screenshot_2024_12_28_105536_1_31_6 {
  background: #d3d3d3 url(<path-to-image>) 50% / cover no-repeat;
  flex-shrink: 0;
  width: 334.539px;
  height: 335.043px;
}
.Rectangle_11_31_7 {
  background: #ee0909;
  flex-shrink: 0;
  width: 385.364px;
  height: 53.076px;
}
.ChristmasCelebration_31_9 {
  color: #fff;
  flex-shrink: 0;
  width: 322.311px;
  height: 43.124px;
  font-family: Inter;
  font-size: 24px;
  font-style: normal;
  font-weight: 900;
  line-height: normal;
  display: inline-block;
}

import React from 'react';
import './App.css';
import IPhone_16Pro_2 from './components/IPhone_16Pro_2';

function App() {
  return (
    <>
      <IPhone_16Pro_2 />
    </>
  );
}

export default App;
import React from 'react';
import styles from '../styles/IPhone_16Pro_2.module.css';


export default function IPhone_16Pro_2() {
  return (
    <div className={styles.IPhone_16Pro_2_1_3}>
      <div className={styles.Screenshot_2024_12_28_104656_2_31_3}></div>
      <div className={styles.Rectangle_7_2_9}></div>
      <div className={styles.Rectangle_9_2_11}></div><span className={styles.RegisterNow_2_13}>REGISTER NOW</span><span className={styles.On_31StDec_2_14}>ON 31ST DEC</span>
      <div className={styles.Rectangle_10_2_15}></div><span className={styles.AllAreWelcome_2_18}>ALL ARE WELCOME</span>
      <div className={styles.Screenshot_2024_12_28_110536_1_31_12}></div>
    </div>
  );
}
@import "https://fonts.googleapis.com/css?family=Inter:1,400&display=swap";
.IPhone_16Pro_2_1_3 {
  background: #f3a4a4;
  width: 100%;
  height: 100%;
  overflow: hidden;
}
.Screenshot_2024_12_28_104656_2_31_3 {
  background: #d3d3d3 url(<path-to-image>) 50% / cover no-repeat;
  flex-shrink: 0;
  width: 393.346px;
  height: 116.045px;
}
.Rectangle_7_2_9 {
  background: #ee0909;
  flex-shrink: 0;
  width: 319px;
  height: 58px;
}
.Rectangle_9_2_11 {
  background: #ee0909;
  flex-shrink: 0;
  width: 309px;
  height: 65px;
}
.RegisterNow_2_13 {
  color: #fff;
  flex-shrink: 0;
  width: 319px;
  height: 58px;
  font-family: Inter;
  font-size: 30px;
  font-style: italic;
  font-weight: 400;
  line-height: normal;
  display: inline-block;
}
.On_31StDec_2_14 {
  color: #fff;
  flex-shrink: 0;
  width: 311px;
  height: 63px;
  font-family: Inter;
  font-size: 30px;
  font-style: italic;
  font-weight: 400;
  line-height: normal;
  display: inline-block;
}
.Rectangle_10_2_15 {
  background: #ee0909;
  flex-shrink: 0;
  width: 340px;
  height: 66px;
}
.AllAreWelcome_2_18 {
  color: #fff;
  flex-shrink: 0;
  width: 339px;
  height: 69px;
  font-family: Inter;
  font-size: 30px;
  font-style: italic;
  font-weight: 400;
  line-height: normal;
  display: inline-block;
}
.Screenshot_2024_12_28_110536_1_31_12 {
  background: #d3d3d3 url(<path-to-image>) 50% / cover no-repeat;
  flex-shrink: 0;
  width: 309.581px;
  height: 217.28px;
}
import React from 'react';
import './App.css';
import IPhone_16Pro_3 from './components/IPhone_16Pro_3';

function App() {
  return (
    <>
      <IPhone_16Pro_3 />
    </>
  );
}

export default App;

import React from 'react';
import styles from '../styles/IPhone_16Pro_3.module.css';


export default function IPhone_16Pro_3() {
  return (
    <div className={styles.IPhone_16Pro_3_1_4}><span className={styles.NameRollNoClassSectionPhoneNo_1_10}>NAME:


        ROLL.NO:


        CLASS:


        SECTION:


        PHONE NO:





      </span>
      <div className={styles.Rectangle_2_2_2}></div>
      <div className={styles.Rectangle_4_2_4}></div>
      <div className={styles.Rectangle_5_2_5}></div>
      <div className={styles.Rectangle_6_2_6}></div>
      <div className={styles.Rectangle_3_2_3}></div>
      <div className={styles.Screenshot_2024_12_28_104656_3_31_4}></div>
    </div>
  );
}
@import "https://fonts.googleapis.com/css?family=Inter:0,undefined&display=swap";
.IPhone_16Pro_3_1_4 {
  background: #f3a4a4;
  width: 100%;
  height: 100%;
  overflow: hidden;
}
.NameRollNoClassSectionPhoneNo_1_10 {
  color: #fff;
  font-family: Inter;
  font-size: 24px;
  font-style: normal;
  font-weight: 800;
  line-height: normal;
  display: inline-block;
}
.Rectangle_2_2_2 {
  background: #ee0909;
  flex-shrink: 0;
  width: 193px;
  height: 37px;
}
.Rectangle_4_2_4 {
  background: #ee0909;
  flex-shrink: 0;
  width: 184px;
  height: 39px;
}
.Rectangle_5_2_5 {
  background: #ee0909;
  flex-shrink: 0;
  width: 182px;
  height: 41px;
}
.Rectangle_6_2_6 {
  background: #ee0909;
  flex-shrink: 0;
  width: 175px;
  height: 42px;
}
.Rectangle_3_2_3 {
  background: #ee0909;
  flex-shrink: 0;
  width: 186px;
  height: 45.859px;
}
.Screenshot_2024_12_28_104656_3_31_4 {
  background: #d3d3d3 url(<path-to-image>) 50% / cover no-repeat;
  flex-shrink: 0;
  width: 394.208px;
  height: 114.95px;
}

import React from 'react';
import './App.css';
import IPhone_16Pro_4 from './components/IPhone_16Pro_4';

function App() {
  return (
    <>
      <IPhone_16Pro_4 />
    </>
  );
}

export default App;

import React from 'react';
import styles from '../styles/IPhone_16Pro_4.module.css';


export default function IPhone_16Pro_4() {
  return (
    <div className={styles.IPhone_16Pro_4_8_21}>
      <div className={styles.Screenshot_2024_12_28_104656_4_31_5}></div><span className={styles.ThankYou_2_8}>THANK YOU</span>
      <div className={styles.Screenshot_2024_12_28_110605_1_31_11}></div>
    </div>
  );
}

@import "https://fonts.googleapis.com/css?family=Inter:1,700&display=swap";
.Screenshot_2024_12_28_104656_4_31_5 {
  background: #d3d3d3 url(<path-to-image>) 50% / cover no-repeat;
  width: 401.058px;
  height: 118.32px;
}
.ThankYou_2_8 {
  color: #fff;
  width: 318.076px;
  height: 67.601px;
  font-family: Inter;
  font-size: 48px;
  font-style: italic;
  font-weight: 700;
  line-height: normal;
  display: inline-block;
  transform: rotate(-0.848deg);
}
.Screenshot_2024_12_28_110605_1_31_11 {
  background: #d3d3d3 url(<path-to-image>) 50% / cover no-repeat;
  width: 311.822px;
  height: 298.202px;
}



## OUTPUT:

![alt text](<Screenshot (85).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
