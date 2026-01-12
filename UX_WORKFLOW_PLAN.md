# RelationshipIQ - UX Workflow & Engagement Plan

**Based on:** UX_ENGAGEMENT_ANALYSIS.md + ui-ux-mockups.md  
**Goal:** Create engaging, habit-forming user experience with daily check-ins and gamification

---

## COMPLETE USER JOURNEY MAP

### Phase 1: First-Time User (Day 1)

```
Download App
    ↓
Splash Screen (2s)
    ↓
Welcome Carousel (3 screens)
    ↓
Sign Up / Login
    ↓
Onboarding Pathway Selection
    ↓
Quick Profile Setup
    ↓
ECR-12 Assessment (5-7 min)
    ↓
Assessment Results
    ↓
Goal Selection
    ↓
→ DASHBOARD (First Experience)
```

### Phase 2: Daily Active User (Day 2+)

```
Open App
    ↓
DAILY CHECK-IN MODAL (NEW!)
"How's your heart today?" 💙
    ↓
Select Mood (1 tap)
    ↓
Optional: Quick Note
    ↓
CELEBRATION ANIMATION ✨
"🔥 7-day streak!"
    ↓
→ DASHBOARD (Personalized)
    ↓
[User explores features]
    ↓
Close App
    ↓
[Evening: Push Notification]
"Don't lose your 15-day streak! 🔥"
```

---

## NEW ENGAGEMENT FEATURES

### 1. DAILY CHECK-IN (Core Hook)

**Trigger:** App open (if not completed today)

**Screen Flow:**
```
┌─────────────────────────────────────┐
│                                     │
│      How's Your Heart Today? 💙     │
│                                     │
│  ┌─────────────────────────────┐   │
│  │                             │   │
│  │  😊  Great                  │   │
│  │  🙂  Good                   │   │
│  │  😐  Okay                   │   │
│  │  😔  Struggling             │   │
│  │  💔  Difficult              │   │
│  │                             │   │
│  └─────────────────────────────┘   │
│                                     │
│  [Skip for now]                     │
└─────────────────────────────────────┘
```

**After Selection:**
```
┌─────────────────────────────────────┐
│                                     │
│     Want to add a quick note?       │
│                                     │
│  ┌─────────────────────────────┐   │
│  │ What's on your mind?        │   │
│  │ [                         ] │   │
│  │                             │   │
│  └─────────────────────────────┘   │
│                                     │
│  [Save]              [Skip]         │
└─────────────────────────────────────┘
```

**Celebration:**
```
┌─────────────────────────────────────┐
│                                     │
│            ✨ ✨ ✨                 │
│                                     │
│         Great work! 🎉              │
│                                     │
│      🔥 7-day streak!               │
│                                     │
│   You've checked in 5 out of 7      │
│   days this week                    │
│                                     │
│         [Continue] ────────         │
└─────────────────────────────────────┘
```

---

### 2. ENHANCED DASHBOARD (New Layout)

```
┌─────────────────────────────────────┐
│ ☰                            🔔 ●   │
│                                     │
│  Good morning, Sarah! 🌅            │
│  You're building great habits       │
│                                     │
│  ┌─────────────────────────────┐   │
│  │ 🔥 YOUR STREAK              │   │
│  │                             │   │
│  │      7 DAYS                 │   │
│  │                             │   │
│  │  M  T  W  T  F  S  S        │   │
│  │  ✓  ✓  ✓  ✓  ✓  ✓  ✓        │   │
│  │                             │   │
│  │  Next milestone: 14 days 🏆 │   │
│  └─────────────────────────────┘   │
│                                     │
│  ┌─────────────────────────────┐   │
│  │ 📊 RELATIONSHIP HEALTH      │   │
│  │                             │   │
│  │        78/100               │   │
│  │    ●●●●●●●●○○○○○○○○         │   │
│  │                             │   │
│  │  ↑ +5 from last week        │   │
│  │                             │   │
│  │  [View Details] ────        │   │
│  └─────────────────────────────┘   │
│                                     │
│  ┌─────────────────────────────┐   │
│  │ 🏆 RECENT ACHIEVEMENTS      │   │
│  │                             │   │
│  │  🎖️ One Week Strong         │   │
│  │  📝 10 Journal Entries      │   │
│  │  📊 First Assessment        │   │
│  │                             │   │
│  │  [View All Badges] ────     │   │
│  └─────────────────────────────┘   │
│                                     │
│  ┌─────────────────────────────┐   │
│  │ 💭 TODAY'S INSIGHT          │   │
│  │                             │   │
│  │  "You've felt 'Good' 5 out  │   │
│  │  of 7 days this week. Your  │   │
│  │  mood improves on weekends."│   │
│  │                             │   │
│  │  [Learn More] ────          │   │
│  └─────────────────────────────┘   │
│                                     │
│  ┌─────────────────────────────┐   │
│  │ 📚 RECOMMENDED FOR YOU      │   │
│  │                             │   │
│  │  🗣️ Communication Basics    │   │
│  │  ●●●○○○○○○○ 3/10 lessons   │   │
│  │                             │   │
│  │  [Continue Learning] ────   │   │
│  └─────────────────────────────┘   │
│                                     │
└─────────────────────────────────────┘
```

---

### 3. GAMIFICATION SYSTEM

#### A. Streak Tracker

**Visual:**
```
┌─────────────────────────────────────┐
│  [←]  Your Streak                   │
│                                     │
│            🔥 7 DAYS                │
│                                     │
│  ┌─────────────────────────────┐   │
│  │  M   T   W   T   F   S   S  │   │
│  │  ✓   ✓   ✓   ✓   ✓   ✓   ✓  │   │
│  └─────────────────────────────┘   │
│                                     │
│  Current Streak: 7 days             │
│  Longest Streak: 12 days            │
│  Total Check-ins: 45                │
│                                     │
│  ┌─────────────────────────────┐   │
│  │ NEXT MILESTONES             │   │
│  │                             │   │
│  │  14 days → "Two Week Warrior"│  │
│  │  ●●●●●●●○○○○○○○ 50%         │   │
│  │                             │   │
│  │  30 days → "Monthly Master" │   │
│  │  ●●●○○○○○○○○○○○ 23%         │   │
│  └─────────────────────────────┘   │
│                                     │
│  ┌─────────────────────────────┐   │
│  │ 🛡️ STREAK PROTECTION        │   │
│  │                             │   │
│  │  You have 1 freeze available│   │
│  │  (Unlocked at 7-day streak) │   │
│  │                             │   │
│  │  Miss a day without losing  │   │
│  │  your streak!               │   │
│  └─────────────────────────────┘   │
└─────────────────────────────────────┘
```

#### B. Badge System

**Badge Gallery:**
```
┌─────────────────────────────────────┐
│  [←]  Achievements                  │
│                                     │
│  ┌─────────────────────────────┐   │
│  │ 🏆 EARNED (8/25)            │   │
│  │                             │   │
│  │  🎖️  First Check-in         │   │
│  │  🔥  3-Day Streak           │   │
│  │  💪  One Week Strong        │   │
│  │  📝  First Journal Entry    │   │
│  │  📊  First Assessment       │   │
│  │  🧠  ECR-12 Complete        │   │
│  │  💬  10 Journal Entries     │   │
│  │  ⭐  Mood Improver          │   │
│  └─────────────────────────────┘   │
│                                     │
│  ┌─────────────────────────────┐   │
│  │ 🔒 LOCKED (17/25)           │   │
│  │                             │   │
│  │  🏅  Two Week Warrior       │   │
│  │     Complete 14-day streak  │   │
│  │     ●●●●●●●○○○○○○○ 50%      │   │
│  │                             │   │
│  │  👑  Monthly Master         │   │
│  │     Complete 30-day streak  │   │
│  │     ●●●○○○○○○○○○○○ 23%      │   │
│  │                             │   │
│  │  🌟  Perfect Week           │   │
│  │     7/7 check-ins in a week │   │
│  │     ●●●●●●●○ 6/7 days       │   │
│  └─────────────────────────────┘   │
└─────────────────────────────────────┘
```

#### C. Relationship Health Score

**Score Dashboard:**
```
┌─────────────────────────────────────┐
│  [←]  Relationship Health           │
│                                     │
│  ┌─────────────────────────────┐   │
│  │                             │   │
│  │         78/100              │   │
│  │                             │   │
│  │    ●●●●●●●●○○○○○○○○         │   │
│  │                             │   │
│  │      THRIVING 🌟            │   │
│  │                             │   │
│  │  ↑ +5 from last week        │   │
│  └─────────────────────────────┘   │
│                                     │
│  SCORE BREAKDOWN                    │
│                                     │
│  ┌─────────────────────────────┐   │
│  │ Daily Check-ins      +14    │   │
│  │ ●●●●●●●○○○○○○○ 5/7 days     │   │
│  │                             │   │
│  │ Positive Mood        +10    │   │
│  │ ●●●●●○○○○○ 5/7 days         │   │
│  │                             │   │
│  │ Assessments          +15    │   │
│  │ ●●●○○○○○○○ 3 completed      │   │
│  │                             │   │
│  │ Journal Entries      +12    │   │
│  │ ●●●●●●○○○○ 12 entries       │   │
│  │                             │   │
│  │ Streak Bonus         +10    │   │
│  │ ●●●●●●●○○○ 7-day streak     │   │
│  │                             │   │
│  │ Improvement Trend    +5     │   │
│  │ ↑ Mood trending up          │   │
│  └─────────────────────────────┘   │
│                                     │
│  ┌─────────────────────────────┐   │
│  │ 📈 PROGRESS OVER TIME       │   │
│  │                             │   │
│  │  100│                       │   │
│  │   80│         ●●●           │   │
│  │   60│     ●●●               │   │
│  │   40│ ●●●                   │   │
│  │   20│                       │   │
│  │    0└─────────────────────  │   │
│  │     W1  W2  W3  W4          │   │
│  └─────────────────────────────┘   │
└─────────────────────────────────────┘
```

---

### 4. MOOD TRACKING & INSIGHTS

**Weekly Mood Graph:**
```
┌─────────────────────────────────────┐
│  [←]  Mood Trends                   │
│                                     │
│  THIS WEEK                          │
│                                     │
│  ┌─────────────────────────────┐   │
│  │ 😊│         ●               │   │
│  │ 🙂│     ●       ●           │   │
│  │ 😐│ ●               ●       │   │
│  │ 😔│                         │   │
│  │ 💔│                         │   │
│  │   └─────────────────────    │   │
│  │    M  T  W  T  F  S  S      │   │
│  └─────────────────────────────┘   │
│                                     │
│  INSIGHTS                           │
│                                     │
│  ┌─────────────────────────────┐   │
│  │ 💡 You tend to feel better  │   │
│  │    on weekends              │   │
│  │                             │   │
│  │ 💡 Your mood improved after │   │
│  │    completing exercises     │   │
│  │                             │   │
│  │ 💡 5 out of 7 days were     │   │
│  │    positive this week       │   │
│  └─────────────────────────────┘   │
│                                     │
│  COMPARE TO LAST WEEK               │
│                                     │
│  ┌─────────────────────────────┐   │
│  │ This Week:  😊 71% positive │   │
│  │ Last Week:  😐 57% positive │   │
│  │                             │   │
│  │ ↑ +14% improvement! 🎉      │   │
│  └─────────────────────────────┘   │
└─────────────────────────────────────┘
```

---

### 5. PUSH NOTIFICATION STRATEGY

#### Daily Check-in Reminder
```
Time: 8:00 PM (user's preferred time)
Title: "How's your heart today? 💙"
Body: "Quick check-in (10 seconds)"
Action: Opens Daily Check-in modal
```

#### Streak Protection
```
Time: 6:00 PM (if not checked in yet)
Title: "Don't lose your 15-day streak! 🔥"
Body: "Quick check-in to keep it going"
Action: Opens Daily Check-in modal
```

#### Milestone Celebration
```
Time: Immediately after achievement
Title: "🎉 You've earned 'One Week Strong' badge!"
Body: "Tap to see your achievement"
Action: Opens Badge Gallery
```

#### Weekly Insight
```
Time: Sunday 7:00 PM
Title: "Your week in review 📊"
Body: "Mood improved 20% this week!"
Action: Opens Mood Trends
```

#### Re-engagement
```
Time: After 3 days of inactivity
Title: "We miss you! 🌱"
Body: "Your relationship growth is waiting"
Action: Opens Dashboard
```

---

## COMPLETE FEATURE INTEGRATION

### Updated Navigation

```
┌─────────────────────────────────────┐
│                                     │
│  🏠 Home        (Dashboard)         │
│  📊 Progress    (NEW!)              │
│  📝 Journal                         │
│  🧠 Assessments                     │
│  👤 Profile                         │
│                                     │
└─────────────────────────────────────┘
```

### Progress Tab (NEW)

```
┌─────────────────────────────────────┐
│  Progress                    [?]    │
│                                     │
│  ┌─────────────────────────────┐   │
│  │ 🔥 STREAK                   │   │
│  │                             │   │
│  │      7 DAYS                 │   │
│  │  M  T  W  T  F  S  S        │   │
│  │  ✓  ✓  ✓  ✓  ✓  ✓  ✓        │   │
│  │                             │   │
│  │  [View Details] ────        │   │
│  └─────────────────────────────┘   │
│                                     │
│  ┌─────────────────────────────┐   │
│  │ 📊 HEALTH SCORE             │   │
│  │                             │   │
│  │      78/100                 │   │
│  │  ●●●●●●●●○○○○○○○○           │   │
│  │                             │   │
│  │  [View Breakdown] ────      │   │
│  └─────────────────────────────┘   │
│                                     │
│  ┌─────────────────────────────┐   │
│  │ 📈 MOOD TRENDS              │   │
│  │                             │   │
│  │  [Weekly graph preview]     │   │
│  │                             │   │
│  │  [View Full Trends] ────    │   │
│  └─────────────────────────────┘   │
│                                     │
│  ┌─────────────────────────────┐   │
│  │ 🏆 ACHIEVEMENTS             │   │
│  │                             │   │
│  │  🎖️ 🔥 💪 📝 📊 🧠 💬 ⭐   │   │
│  │                             │   │
│  │  8/25 badges earned         │   │
│  │                             │   │
│  │  [View All] ────            │   │
│  └─────────────────────────────┘   │
└─────────────────────────────────────┘
```

---

## IMPLEMENTATION PHASES

### Phase 1: Daily Check-in (Week 1-2)
**Priority: CRITICAL**

**Backend:**
- [ ] Daily check-in collection schema
- [ ] Streak calculation logic
- [ ] Check-in history endpoint
- [ ] Mood analytics endpoint

**Frontend:**
- [ ] Daily check-in modal component
- [ ] Mood selection UI
- [ ] Optional note input
- [ ] Celebration animation
- [ ] Skip functionality

**Testing:**
- [ ] Modal triggers on app open
- [ ] Only shows once per day
- [ ] Streak calculation accurate
- [ ] Data saves to Firestore

---

### Phase 2: Streak & Gamification (Week 3-4)
**Priority: HIGH**

**Backend:**
- [ ] Streak tracking schema
- [ ] Freeze system logic
- [ ] Badge unlock logic
- [ ] Achievement notifications

**Frontend:**
- [ ] Streak display on dashboard
- [ ] Streak detail screen
- [ ] Badge gallery
- [ ] Achievement unlock animations
- [ ] Progress tab

**Testing:**
- [ ] Streak increments correctly
- [ ] Freeze system works
- [ ] Badges unlock at right times
- [ ] Animations smooth

---

### Phase 3: Health Score & Analytics (Week 5-6)
**Priority: MEDIUM**

**Backend:**
- [ ] Score calculation algorithm
- [ ] Component breakdown logic
- [ ] Historical data tracking
- [ ] Trend analysis

**Frontend:**
- [ ] Health score widget
- [ ] Score breakdown screen
- [ ] Progress graphs
- [ ] Comparison views

**Testing:**
- [ ] Score calculates correctly
- [ ] Updates in real-time
- [ ] Graphs render properly
- [ ] Historical data accurate

---

### Phase 4: Mood Insights & Personalization (Week 7-8)
**Priority: MEDIUM**

**Backend:**
- [ ] Mood pattern analysis
- [ ] Correlation detection
- [ ] Insight generation
- [ ] Personalized recommendations

**Frontend:**
- [ ] Mood trend graphs
- [ ] Insight cards
- [ ] Weekly summaries
- [ ] Comparison views

**Testing:**
- [ ] Patterns detected correctly
- [ ] Insights are meaningful
- [ ] Recommendations relevant
- [ ] UI is clear

---

### Phase 5: Push Notifications (Week 9-10)
**Priority: HIGH**

**Backend:**
- [ ] Notification scheduling
- [ ] User preference storage
- [ ] Timing optimization
- [ ] Delivery tracking

**Frontend:**
- [ ] Notification permissions
- [ ] Settings UI
- [ ] Deep linking
- [ ] Badge updates

**Testing:**
- [ ] Notifications deliver
- [ ] Timing is correct
- [ ] Deep links work
- [ ] User can disable

---

## SUCCESS METRICS

### Week 1-2 (Daily Check-in Launch)
- [ ] 80%+ users complete first check-in
- [ ] 60%+ users check in 5+ times in week 1
- [ ] Average time to complete: <30 seconds
- [ ] Skip rate: <20%

### Week 3-4 (Gamification Launch)
- [ ] Average streak length: 5+ days
- [ ] 50%+ users earn at least 3 badges
- [ ] Session frequency: 5+ times per week
- [ ] 7-day retention: 60%+

### Week 5-6 (Health Score Launch)
- [ ] 70%+ users view score breakdown
- [ ] Average score improvement: +10 points/month
- [ ] Users check score 3+ times per week
- [ ] Positive feedback on insights

### Week 7-8 (Mood Insights Launch)
- [ ] 80%+ users view mood trends
- [ ] Insights engagement: 50%+ click-through
- [ ] Users find insights valuable (survey)
- [ ] Mood tracking completion: 70%+

### Week 9-10 (Notifications Launch)
- [ ] Notification opt-in: 70%+
- [ ] Open rate: 30%+
- [ ] Streak protection effective: 40% save streak
- [ ] User satisfaction: 4+ stars

---

## DESIGN SYSTEM UPDATES

### New Components Needed

**1. Daily Check-in Modal**
- Mood selector (5 options)
- Optional text input
- Skip button
- Save button
- Celebration animation

**2. Streak Display**
- Fire emoji + number
- Weekly calendar view
- Milestone progress
- Freeze indicator

**3. Badge Card**
- Badge icon
- Badge name
- Description
- Unlock date
- Progress bar (for locked)

**4. Health Score Widget**
- Circular progress
- Score number
- Color gradient
- Trend indicator
- Tap to expand

**5. Mood Graph**
- Line chart
- 7-day view
- Emoji markers
- Comparison overlay

**6. Celebration Animation**
- Confetti effect
- Badge fly-in
- Score count-up
- Haptic feedback

---

## TECHNICAL REQUIREMENTS

### Backend (Firebase)

**New Collections:**
```typescript
// Daily Check-ins
dailyCheckIns: {
  userId: string;
  date: string; // YYYY-MM-DD
  mood: 1 | 2 | 3 | 4 | 5;
  moodLabel: string;
  note?: string;
  timestamp: Date;
  streak: number;
}

// User Streaks
userStreaks: {
  userId: string;
  currentStreak: number;
  longestStreak: number;
  lastCheckInDate: string;
  freezesAvailable: number;
  freezesUsed: number;
  totalCheckIns: number;
}

// Badges
userBadges: {
  userId: string;
  badgeId: string;
  badgeName: string;
  unlockedAt: Date;
  category: string;
}

// Health Scores
healthScores: {
  userId: string;
  score: number; // 0-100
  components: {
    checkIns: number;
    mood: number;
    assessments: number;
    journal: number;
    streak: number;
    trend: number;
  };
  calculatedAt: Date;
}
```

**New Cloud Functions:**
- `calculateStreak(userId)` - Daily cron job
- `unlockBadges(userId)` - Triggered on actions
- `calculateHealthScore(userId)` - Real-time
- `generateInsights(userId)` - Weekly cron job
- `scheduleNotifications(userId)` - Daily cron job

### Frontend (React Native)

**New Screens:**
- `DailyCheckInModal.tsx`
- `StreakDetailScreen.tsx`
- `BadgeGalleryScreen.tsx`
- `HealthScoreScreen.tsx`
- `MoodTrendsScreen.tsx`
- `ProgressTabScreen.tsx`

**New Components:**
- `MoodSelector.tsx`
- `StreakDisplay.tsx`
- `BadgeCard.tsx`
- `HealthScoreWidget.tsx`
- `MoodGraph.tsx`
- `CelebrationAnimation.tsx`
- `ProgressBar.tsx`
- `AchievementToast.tsx`

**New Services:**
- `checkInService.ts` - Daily check-in logic
- `streakService.ts` - Streak tracking
- `badgeService.ts` - Badge management
- `healthScoreService.ts` - Score calculation
- `insightService.ts` - Insight generation
- `notificationService.ts` - Push notifications

**Libraries Needed:**
- `react-native-reanimated` - Animations
- `react-native-chart-kit` - Graphs
- `react-native-push-notification` - Notifications
- `@react-native-async-storage/async-storage` - Local caching
- `react-native-haptic-feedback` - Haptics

---

## NEXT STEPS

1. **Review this plan** - Get approval on approach
2. **Create HTML visualization** - Interactive workflow view
3. **Start Phase 1** - Implement Daily Check-in
4. **Beta test** - Get user feedback
5. **Iterate** - Refine based on data

---

**Ready to proceed?** Let me know if you want me to:
1. Create the interactive HTML visualization
2. Start implementing Phase 1
3. Adjust the plan based on feedback
