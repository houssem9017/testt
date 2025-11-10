# 🎨 UNISPHERE BRANDING IMPLEMENTATION

## Brand Identity Applied

### Logo Usage
- **Logo Site Web**: `Logo_Site_Web.png` - Used in navigation and login/register pages
- **Logo Groupe**: `Logo_Groupe_.png` - Used in hero section of homepage

### Color Palette Implementation

| Color | Hex Code | Usage | Brand Value |
|-------|----------|-------|-------------|
| Burgundy | #2E0014 | Primary navigation, headers | Unity |
| Brown | #442220 | Secondary buttons, accents | Compassion |
| Olive | #809848 | Primary buttons, highlights | Action |
| Forest Green | #172815 | Success states, education | Education |
| Light Pink | #F3E4E2 | Backgrounds, cards | Neutral |

### Typography
- Primary Font: Segoe UI (fallback: Tahoma, Geneva, Verdana, sans-serif)
- Consistent with Unisphere brand guidelines

### Brand Values Integration

Each game is associated with a brand value:

1. **Quiz QCU** → Unity (#2E0014)
2. **Jeu Société** → Compassion (#442220)
3. **Jeu Paix** → Action (#809848)
4. **Jeu Inclusion** → Education (#172815)

## Files Modified

### CSS Files
- ✅ `src/assets/css/unisphere-brand.css` - Complete brand stylesheet created

### Frontend Pages
- ✅ `View/Frontoffice/index.php` - Homepage with logos and brand colors
- ✅ `View/Frontoffice/login.php` - Branded login page
- ✅ `View/Frontoffice/register.php` - Branded registration page

### Backend Pages
- ✅ `View/Backoffice/dashboard.php`
- ✅ `View/Backoffice/profile.php`
- ✅ `View/Backoffice/userList.php`
- ✅ `View/Backoffice/gameResults.php`
- ✅ `View/Backoffice/leaderboard.php`
- ✅ `View/Backoffice/settings.php`
- ✅ `View/Backoffice/includes/sidebar.php` - Logo added

### Assets
- ✅ Logos copied to `src/assets/images/brand/logo/`

## Brand Elements

### Navigation
- Background: Burgundy (#2E0014)
- Logo: Left-aligned with brand name
- Links: Light text with olive hover

### Buttons
- **Primary**: Olive green (#809848) - Main CTAs
- **Secondary**: Brown (#442220) - Alternative actions
- **Success**: Forest green (#172815) - Confirmations

### Cards
- Background: Light gradient (F3E4E2 to white)
- Border: Optional olive accent
- Shadow: Custom "shadow-brand" class
- Game cards have colored left border matching their value

### Badges
- Unity Badge: Burgundy background
- Compassion Badge: Brown background
- Action Badge: Olive background
- Education Badge: Forest green background

## CSS Classes Available

### Colors
```css
.text-burgundy
.text-olive
.text-forest
.bg-burgundy
.bg-olive  
.bg-forest
```

### Brand Values
```css
.value-unity
.value-compassion
.value-action
.value-education
```

### Badges
```css
.badge-unity
.badge-compassion
.badge-action
.badge-education
```

### Game Cards
```css
.game-quiz
.game-societe
.game-paix
.game-inclusion
```

### Utilities
```css
.shadow-brand - Custom shadow with olive tint
.border-olive - Olive border
.border-burgundy - Burgundy border
.brand-logo - Standard logo size (50px)
.brand-logo-large - Large logo (80px)
```

## Gradients

### Main Gradient
```css
background: linear-gradient(135deg, #809848 0%, #172815 100%);
```

### Hero Gradient
```css
background: linear-gradient(135deg, #2E0014 0%, #442220 50%, #809848 100%);
```

## Brand Compliance Checklist

- [x] Official logos used
- [x] Color palette applied consistently
- [x] Typography matches guidelines
- [x] Brand values integrated into design
- [x] "Unir, Comprendre, Agir" tagline displayed
- [x] Consistent visual identity across all pages
- [x] Accessible color contrasts maintained
- [x] Responsive design preserved

## Usage Notes

1. **Logo**: Always use provided PNG files, maintain aspect ratio
2. **Colors**: Use CSS variables (--primary-olive, etc.) for consistency
3. **Buttons**: Primary actions use olive, secondary use brown
4. **Brand Values**: Each game should display its associated value badge
5. **Tagline**: "Unir, Comprendre, Agir" should appear on main pages

## Testing

Test the branding on:
- [x] Homepage (Frontend)
- [x] Login page
- [x] Registration page
- [x] Admin Dashboard
- [x] All game pages should follow same pattern

---

**Unisphere Brand Applied Successfully!** 🎨
*Unir, Comprendre, Agir*
