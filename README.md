# Event_Invitation
## Nanda Kishore R - 212222060157

## Aim

To design a visually appealing and professional event invitation card using HTML and CSS that effectively communicates event details while demonstrating fundamental web development skills including layout design, styling, and responsive web design principles.

## Project Overview
  
This project creates an elegant digital invitation card for an Annual Alumni Meet event, featuring modern design elements, gradient backgrounds, interactive components, and mobile-responsive layout.

## Steps 

### Step 1: HTML Structure Setup

- Create HTML5 document with DOCTYPE, head, and body
- Link external CSS stylesheet
- Set up main container div with class "invite-card"

### Step 2: Content Creation

- Add header section with event title, subtitle, and tagline
- Insert event image (alumni.jpg)
- Create event details section with date, time, venue
- Add event highlights, dress code, and RSVP sections

### Step 3: CSS Styling Implementation

- Apply gradient backgrounds and modern styling
- Style typography with custom fonts, colors, and shadows
- Add decorative elements like borders and icons
- Create responsive layout with flexbox

### Step 4: Interactive Elements & Responsiveness
- Add hover effects and transitions for buttons
- Implement responsive design with media queries
- Style RSVP button with gradient and hover animations
- Ensure mobile compatibility and proper spacing

## HTML Code

```
<!DOCTYPE html>
<html>
<head>
    <title>Event Invitation</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="invite-card">
        <div class="header-section">
            <h1>Annual Alumni Meet 2025</h1>
            <h3>Reconnect & Celebrate Together</h3>
            <p class="tagline">"Once a student, Always family"</p>
        </div>
        
        <img src="alumni.jpg" alt="Event Banner">
        
        <div class="event-details">
            <div class="detail-item">
                <p><strong>Date:</strong> August 25, 2025</p>
            </div>
            <div class="detail-item">
                <p><strong>Time:</strong> 6:00 PM - 11:00 PM</p>
            </div>
            <div class="detail-item">
                <p><strong>Venue:</strong> College Auditorium</p>
            </div>
        </div>
        
        <div class="rsvp-section">
            <p><strong>Contact:</strong> Nanda Kishore - 9324440486</p>
            <button class="rsvp-btn">Confirm Attendance</button>
        </div>
    </div>
</body>
</html>
```

## CSS Code:

```
body {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 20px;
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
}

.invite-card {
    max-width: 450px;
    padding: 30px;
    border-radius: 20px;
    box-shadow: 0 15px 35px rgba(0, 0, 0, 0.3);
    background: linear-gradient(145deg, #ffffff, #f0f0f0);
    text-align: center;
    position: relative;
    overflow: hidden;
    transition: transform 0.3s ease;
}

.invite-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 20px 40px rgba(0, 0, 0, 0.4);
}

.invite-card::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    height: 4px;
    background: linear-gradient(90deg, #ff6b6b, #4ecdc4, #45b7d1, #96ceb4);
}

.header-section {
    margin-bottom: 20px;
}

h1 {
    color: #2c3e50;
    margin-bottom: 8px;
    font-size: 28px;
    font-weight: bold;
    text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
}

h3 {
    color: #34495e;
    margin-bottom: 10px;
    font-weight: normal;
    font-size: 16px;
}

.tagline {
    color: #7f8c8d;
    font-style: italic;
    font-size: 13px;
    margin-bottom: 15px;
}

img {
    max-width: 100%;
    height: 120px;
    object-fit: cover;
    border-radius: 12px;
    margin: 15px 0;
    box-shadow: 0 6px 12px rgba(0,0,0,0.2);
    transition: transform 0.3s ease;
}

img:hover {
    transform: scale(1.05);
}

.event-details {
    background-color: #f8f9fa;
    padding: 15px;
    border-radius: 12px;
    margin: 20px 0;
    border: 2px solid #e9ecef;
}

.detail-item {
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 10px 0;
}

.icon {
    font-size: 18px;
    margin-right: 8px;
}

p {
    margin: 3px 0;
    font-size: 14px;
    color: #2c3e50;
}

strong {
    color: #e74c3c;
}

.rsvp-section {
    margin-top: 20px;
    padding: 15px;
    background: linear-gradient(145deg, #f8f9fa, #e9ecef);
    border-radius: 12px;
}

.rsvp-section p {
    font-size: 13px;
    margin-bottom: 15px;
    color: #555;
}

.rsvp-btn {
    background: linear-gradient(45deg, #28a745, #20c997);
    color: white;
    border: none;
    padding: 10px 20px;
    border-radius: 20px;
    font-size: 14px;
    font-weight: bold;
    cursor: pointer;
    transition: all 0.3s ease;
    box-shadow: 0 4px 8px rgba(40, 167, 69, 0.3);
}

.rsvp-btn:hover {
    transform: translateY(-2px);
    box-shadow: 0 6px 15px rgba(40, 167, 69, 0.5);
    background: linear-gradient(45deg, #20c997, #28a745);
}

/* Responsive Design */
@media (max-width: 500px) {
    .invite-card {
        margin: 10px;
        padding: 20px;
        max-width: none;
    }
    
    h1 {
        font-size: 24px;
    }
    
    .detail-item {
        flex-direction: column;
        text-align: center;
    }
    
    .icon {
        margin-right: 0;
        margin-bottom: 3px;
    }
}
```

## Output:

![image](https://github.com/user-attachments/assets/64133ba8-c92f-434f-9037-b43b63ae620d)

## Result:

Thus the invitation card is completed
