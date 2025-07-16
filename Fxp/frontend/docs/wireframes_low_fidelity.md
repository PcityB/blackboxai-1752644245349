# Low-Fidelity Wireframes - Forex Pattern Discovery Framework

## Desktop Layout (≥1366px)

### Dashboard Page
```
┌─────────────────────────────────────────────────────────────────┐
│ [Logo] Forex Pattern Discovery    [Notifications] [User] [Theme] │
├─────────────────────────────────────────────────────────────────┤
│ [Dashboard] [Discovery] [Analysis] [Admin]                      │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│ ┌─────────────────┐ ┌─────────────────┐ ┌─────────────────┐    │
│ │ System Status   │ │ Active Jobs     │ │ Recent Results  │    │
│ │ ● Online        │ │ ⚡ 3 Running    │ │ 📊 5 Completed  │    │
│ │ CPU: 45%        │ │ ⏳ 2 Queued    │ │ 🔍 2 Analyzing  │    │
│ │ Memory: 67%     │ │ ❌ 1 Failed    │ │ ✅ 8 Validated  │    │
│ └─────────────────┘ └─────────────────┘ └─────────────────┘    │
│                                                                 │
│ ┌─────────────────────────────────────────────────────────────┐ │
│ │ Performance Timeline                                        │ │
│ │ [Chart showing system performance over time]                │ │
│ │                                                             │ │
│ └─────────────────────────────────────────────────────────────┘ │
│                                                                 │
│ ┌─────────────────────────────────────────────────────────────┐ │
│ │ Quick Actions                                               │ │
│ │ [Start Discovery] [View Patterns] [Run Analysis] [Export]   │ │
│ └─────────────────────────────────────────────────────────────┘ │
└─────────────────────────────────────────────────────────────────┘
```

### Pattern Discovery Workspace
```
┌─────────────────────────────────────────────────────────────────┐
│ [Navigation Bar]                                                │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│ ┌─────────────────┐ ┌─────────────────────────────────────────┐ │
│ │ Parameters      │ │ Job Monitor                             │ │
│ │                 │ │ ┌─────────────────────────────────────┐ │ │
│ │ Timeframe:      │ │ │ Job ID: abc123                      │ │ │
│ │ [1h ▼]          │ │ │ Status: Running                     │ │ │
│ │                 │ │ │ Progress: ████████░░ 80%            │ │ │
│ │ Window Size:    │ │ │ Started: 10:30 AM                   │ │ │
│ │ [5]             │ │ │ ETA: 2 minutes                      │ │ │
│ │                 │ │ └─────────────────────────────────────┘ │ │
│ │ Grid Size:      │ │                                         │ │
│ │ [10x10 ▼]       │ │ Recent Jobs:                            │ │
│ │                 │ │ • def456 - Completed (5 min ago)       │ │
│ │ Max Patterns:   │ │ • ghi789 - Failed (1 hour ago)         │ │
│ │ [5000]          │ │ • jkl012 - Completed (2 hours ago)     │ │
│ │                 │ │                                         │ │
│ │ [Start Extract] │ │                                         │ │
│ └─────────────────┘ └─────────────────────────────────────────┘ │
│                                                                 │
│ ┌─────────────────────────────────────────────────────────────┐ │
│ │ Pattern Heat Map                                            │ │
│ │ [Interactive grid showing pattern similarity matrix]        │ │
│ │                                                             │ │
│ └─────────────────────────────────────────────────────────────┘ │
│                                                                 │
│ ┌─────────────────────────────────────────────────────────────┐ │
│ │ Pattern Comparison                                          │ │
│ │ [Side-by-side pattern visualizations]                      │ │
│ │                                                             │ │
│ └─────────────────────────────────────────────────────────────┘ │
└─────────────────────────────────────────────────────────────────┘
```

### Pattern Analysis Studio
```
┌─────────────────────────────────────────────────────────────────┐
│ [Navigation Bar]                                                │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│ ┌─────────────────────────────────────────────────────────────┐ │
│ │ Interactive Candlestick Chart                               │ │
│ │ [Plotly.js chart with pattern overlays, zoom, pan]         │ │
│ │                                                             │ │
│ │ Controls: [Zoom] [Pan] [Reset] [Export]                     │ │
│ └─────────────────────────────────────────────────────────────┘ │
│                                                                 │
│ ┌─────────────────┐ ┌─────────────────┐ ┌─────────────────┐    │
│ │ Statistical     │ │ Backtest Config │ │ KPI Tiles       │    │
│ │ Significance    │ │                 │ │                 │    │
│ │                 │ │ Lookback:       │ │ Sharpe: 1.45    │    │
│ │ P-Value: 0.023  │ │ [10 periods]    │ │ Profit: 2.3x    │    │
│ │ T-Stat: 2.45    │ │                 │ │ Win Rate: 67%   │    │
│ │ Significant: ✅  │ │ Stop Loss:      │ │ Max DD: -5.2%   │    │
│ │                 │ │ [2%]            │ │                 │    │
│ │ Confidence:     │ │                 │ │ Avg Trade:      │    │
│ │ 97.7%           │ │ Take Profit:    │ │ +0.8%           │    │
│ │                 │ │ [5%]            │ │                 │    │
│ │                 │ │                 │ │ Total Trades:   │    │
│ │                 │ │ [Run Backtest]  │ │ 234             │    │
│ └─────────────────┘ └─────────────────┘ └─────────────────┘    │
└─────────────────────────────────────────────────────────────────┘
```

## Tablet Layout (768px - 1023px)

### Dashboard Page (Tablet)
```
┌─────────────────────────────────────────────────┐
│ [☰] Forex Pattern Discovery    [🔔] [👤] [🌙]  │
├─────────────────────────────────────────────────┤
│                                                 │
│ ┌─────────────────┐ ┌─────────────────────────┐ │
│ │ System Status   │ │ Active Jobs             │ │
│ │ ● Online        │ │ ⚡ 3 Running ⏳ 2 Queue │ │
│ │ CPU: 45%        │ │ ❌ 1 Failed             │ │
│ │ Memory: 67%     │ │                         │ │
│ └─────────────────┘ └─────────────────────────┘ │
│                                                 │
│ ┌─────────────────────────────────────────────┐ │
│ │ Performance Chart                           │ │
│ │ [Responsive chart]                          │ │
│ └─────────────────────────────────────────────┘ │
│                                                 │
│ ┌─────────────────────────────────────────────┐ │
│ │ Quick Actions                               │ │
│ │ [Start] [View] [Analyze] [Export]           │ │
│ └─────────────────────────────────────────────┘ │
└─────────────────────────────────────────────────┘
```

### Collapsible Sidebar (Tablet)
```
┌─────────────────────────────────────────────────┐
│ [☰] ← Tap to expand sidebar                     │
├─────────────────────────────────────────────────┤
│                                                 │
│ When expanded:                                  │
│ ┌─────────────┐                                │
│ │ Navigation  │                                │
│ │ • Dashboard │                                │
│ │ • Discovery │                                │
│ │ • Analysis  │                                │
│ │ • Admin     │                                │
│ │             │                                │
│ │ [Close ×]   │                                │
│ └─────────────┘                                │
└─────────────────────────────────────────────────┘
```

## Mobile Layout (375px - 767px)

### Dashboard Page (Mobile)
```
┌─────────────────────────────────┐
│ [☰] FX Pattern [🔔] [👤] [🌙]  │
├─────────────────────────────────┤
│                                 │
│ ┌─────────────────────────────┐ │
│ │ System Status               │ │
│ │ ● Online                    │ │
│ │ CPU: 45% | Memory: 67%      │ │
│ └─────────────────────────────┘ │
│                                 │
│ ┌─────────────────────────────┐ │
│ │ Jobs: 3 Running, 2 Queued   │ │
│ │ Results: 5 Complete         │ │
│ └─────────────────────────────┘ │
│                                 │
│ ┌─────────────────────────────┐ │
│ │ Performance                 │ │
│ │ [Simplified chart]          │ │
│ └─────────────────────────────┘ │
│                                 │
│ ┌─────────────────────────────┐ │
│ │ Actions                     │ │
│ │ [Start Discovery]           │ │
│ │ [View Patterns]             │ │
│ │ [Run Analysis]              │ │
│ │ [Export Data]               │ │
│ └─────────────────────────────┘ │
└─────────────────────────────────┘
```

### Pattern Discovery (Mobile)
```
┌─────────────────────────────────┐
│ [☰] Pattern Discovery          │
├─────────────────────────────────┤
│                                 │
│ ┌─────────────────────────────┐ │
│ │ Parameters                  │ │
│ │                             │ │
│ │ Timeframe: [1h ▼]           │ │
│ │ Window Size: [5]            │ │
│ │ Grid Size: [10x10 ▼]        │ │
│ │ Max Patterns: [5000]        │ │
│ │                             │ │
│ │ [Start Extraction]          │ │
│ └─────────────────────────────┘ │
│                                 │
│ ┌─────────────────────────────┐ │
│ │ Current Job                 │ │
│ │ Status: Running             │ │
│ │ Progress: ████████░░ 80%    │ │
│ │ ETA: 2 minutes              │ │
│ └─────────────────────────────┘ │
│                                 │
│ ┌─────────────────────────────┐ │
│ │ Recent Jobs                 │ │
│ │ • Completed (5m ago)        │ │
│ │ • Failed (1h ago)           │ │
│ │ • Completed (2h ago)        │ │
│ └─────────────────────────────┘ │
└─────────────────────────────────┘
```

### Pattern Analysis (Mobile)
```
┌─────────────────────────────────┐
│ [☰] Pattern Analysis           │
├─────────────────────────────────┤
│                                 │
│ ┌─────────────────────────────┐ │
│ │ Candlestick Chart           │ │
│ │ [Touch-optimized chart]     │ │
│ │                             │ │
│ │ [Pinch to zoom]             │ │
│ │ [Swipe to pan]              │ │
│ └─────────────────────────────┘ │
│                                 │
│ ┌─────────────────────────────┐ │
│ │ Statistics                  │ │
│ │ P-Value: 0.023 ✅           │ │
│ │ Confidence: 97.7%           │ │
│ └─────────────────────────────┘ │
│                                 │
│ ┌─────────────────────────────┐ │
│ │ KPIs                        │ │
│ │ Sharpe: 1.45 | Profit: 2.3x│ │
│ │ Win Rate: 67% | DD: -5.2%   │ │
│ └─────────────────────────────┘ │
│                                 │
│ ┌─────────────────────────────┐ │
│ │ Backtest                    │ │
│ │ [Configure & Run]           │ │
│ └─────────────────────────────┘ │
└─────────────────────────────────┘
```

## Navigation Patterns

### Desktop Navigation
- Fixed top navigation bar
- Always visible tabs for main sections
- Breadcrumb navigation for deep pages
- Context-sensitive action buttons

### Tablet Navigation
- Collapsible sidebar triggered by hamburger menu
- Tab bar adapts to available space
- Swipe gestures for navigation between sections

### Mobile Navigation
- Bottom tab bar for main sections
- Hamburger menu for secondary options
- Full-screen modals for complex forms
- Pull-to-refresh for data updates

## Accessibility Features

### Keyboard Navigation
- Tab order follows logical flow
- All interactive elements focusable
- Escape key closes modals/dropdowns
- Arrow keys navigate within components

### Screen Reader Support
- Semantic HTML structure
- ARIA labels for complex components
- Live regions for dynamic updates
- Skip links for main content

### Visual Accessibility
- High contrast mode support
- Scalable text (up to 200%)
- Focus indicators clearly visible
- Color not sole means of communication

## Progressive Disclosure

### Beginner Mode
- Simplified parameter forms
- Guided workflows
- Helpful tooltips and explanations
- Default values for complex settings

### Advanced Mode
- Full parameter control
- Batch operations
- Advanced filtering and sorting
- Raw data export options

### Expert Mode
- API access information
- System internals visibility
- Performance tuning options
- Debug information display
