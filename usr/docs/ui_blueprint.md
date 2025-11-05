# Multiverse App - Full Frontend Screen-by-Screen UI Blueprint

## 1. Onboarding & Signup Flow

### Screen 1: Welcome / App Introduction
- Fullscreen background image or gradient
- Centered logo and tagline
- "Get Started" button
- Bottom: "Already have an account? Log in"

### Screen 2: Signup Method Selection
- Title: "Sign up with"
- Buttons: Email, Phone
- Option: "Continue with Google/Facebook" (optional placeholders)

### Screen 3: Email / Phone Input
- TextField: Email or Phone
- "Next" button disabled until valid input

### Screen 4: OTP Verification (if phone)
- Title: "Enter the code sent to +1•••123"
- 4-digit input boxes
- "Resend code" link with countdown timer
- "Verify" button

### Screen 5: Username & Password
- TextField: Username
- TextField: Password (obscured)
- Show/Hide toggle for password
- "Next" button

### Screen 6: Profile Basics
- Title: "Tell us about yourself"
- Age picker (date picker)
- Gender selection (radio buttons or chips)
- Profile photo upload area (camera / gallery)
- "Next" button

### Screen 7: Select Goals
- Title: "What are you here for?"
- Multiple selectable chips: Create Content, Make Friends, Networking, Dating, Entertainment
- "Next" button

### Screen 8: Universe Theme
- Title: "Choose your universe"
- Grid of images/chips: Social, Creative, Dating, (Gaming - coming soon)
- "Next" button

### Screen 9: Interests Selection
- Title: "Select your interests"
- Search bar
- Scrollable chips: Music, Fitness, Business, Tech, Fashion, Travel...
- "Next" button

### Screen 10: Privacy & Visibility
- Title: "Profile Mode"
- Options: Public, Private, Selective
- Radio buttons + description text
- "Finish" button

---

## 2. Welcome Tour / Story Intro (Optional)
- Swipeable carousel of app features
- Skip link
- "Got it" button leads to Home

---

## 3. Home Feed

### Layout
- AppBar: Logo, Search Icon, Message Icon
- TabBar (sticky): Following, For You, Near You, Creators, Genres
- Body: Infinite PageView or List
  - Each item: mixed media (image, video auto-play)
  - Overlay: like/comment/share icons vertically aligned on right
  - Bottom-left: creator avatar + name + follow button
  - Bottom: caption + hashtags
  - Double-tap like interaction
- Floating Action Button: + to upload


## 4. Discover Page
- AppBar: Title "Discover", Search bar integrated
- Sections (vertical scroll): Trending Categories (horizontal chips), Suggested Creators (horizontal cards), Popular Reels, Trending Audio, Hashtags Explorer (grid), Challenges & Trends
- Each card: image/video thumbnail, title, caption snippet

---

## 5. Video Detail Page

### Layout
- Fullscreen video
- Top-left: back button
- Bottom overlay: video controls (play/pause, progress bar)
- Right side overlay: like, comment, share, bookmark buttons
- Below video: title, creator info with follow button, subscribe section, description with "Show more"
- Tabs or expandable: Comments, Chapters, Related videos list (vertical scroll)
- Contextual buttons: quality, captions, donate, playlist add

---

## 6. Dating / Connect Mode
- Toggle at top bar: Social / Dating
- Tinder-style swipe deck: cards with profile photo/video, name, age, badges below
- Bottom buttons: rewind, dislike, like, super like
- Profile preview: tap card to open full profile modal with multiphoto gallery and prompts

---

## 7. Messaging / Chat
- Chat list screen: avatars, name, last message preview, time, unread badge
- Chat screen:
  - AppBar: profile avatar/name, call icon, info icon
  - Messages: bubbles for text, audio, video, reactions
  - Input area: text input, emoji button, attachment button, mic for audio, camera icon for video message
  - Options button for vanish mode toggle

---

## 8. Profile Screen
- Header: cover image (optional), profile avatar, name, badges, follow/edit button
- Stats: followers, following, posts
- Segmented control: Posts, Reels, Shorts, Liked
- Grid or list layout for content
- Buttons: Edit profile, Settings
- Bio section: hashtags, emojis, links

---

## 9. Camera & Upload
- Camera screen: preview, shutter button, switch camera, flash toggle, timer
- Effects menu: filters, AR effects, green screen, speed control
- Sound library button
- Post-capture editing: trim bar, text sticker picker, auto captions toggle, publish screen with caption, hashtags, universe tag, privacy settings

---

## 10. Library / Saved
- Tabs: Posts, Sounds, Collections, Drafts
- List/grid of saved items
- Edit mode for organizing collections

---

## 11. Main Menu / Settings
- Drawer or bottom sheet with menu items: Profile, My Posts, Matches, Playlists, Downloads, Settings, Help & Safety, Report Center, Creator Studio
- Settings screen: sections for Account, Privacy, Notifications, Ads, Language, Security, Logout

---

## 12. Safety Center
- Screen: Blocked users list, Restricted users list, Report history
- Toggles: AI comment filter, screenshot alerts, vanish chat
- Verify profile CTA

---

**Next Steps:** Implement detailed wireframes based on this blueprint per screen, then generate Flutter widget scaffolds accordingly.