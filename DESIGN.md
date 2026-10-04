---
name: LPBF Defect Vision AI
colors:
  surface: '#0f131c'
  surface-dim: '#0f131c'
  surface-bright: '#353942'
  surface-container-lowest: '#0a0e16'
  surface-container-low: '#181c24'
  surface-container: '#1c2028'
  surface-container-high: '#262a33'
  surface-container-highest: '#31353e'
  on-surface: '#dfe2ee'
  on-surface-variant: '#b9cacb'
  inverse-surface: '#dfe2ee'
  inverse-on-surface: '#2c3039'
  outline: '#849495'
  outline-variant: '#3b494b'
  surface-tint: '#00dbe9'
  primary: '#dbfcff'
  on-primary: '#00363a'
  primary-container: '#00f0ff'
  on-primary-container: '#006970'
  inverse-primary: '#006970'
  secondary: '#ffb95f'
  on-secondary: '#472a00'
  secondary-container: '#ee9800'
  on-secondary-container: '#5b3800'
  tertiary: '#fff3f2'
  on-tertiary: '#68000a'
  tertiary-container: '#ffceca'
  on-tertiary-container: '#ba1b24'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#7df4ff'
  primary-fixed-dim: '#00dbe9'
  on-primary-fixed: '#002022'
  on-primary-fixed-variant: '#004f54'
  secondary-fixed: '#ffddb8'
  secondary-fixed-dim: '#ffb95f'
  on-secondary-fixed: '#2a1700'
  on-secondary-fixed-variant: '#653e00'
  tertiary-fixed: '#ffdad7'
  tertiary-fixed-dim: '#ffb3ad'
  on-tertiary-fixed: '#410004'
  on-tertiary-fixed-variant: '#930013'
  background: '#0f131c'
  on-background: '#dfe2ee'
  surface-variant: '#31353e'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0em
  label-lg:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.06em
  code-data:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 0.75rem
  gutter-lg: 1rem
  margin: 1rem
  margin-lg: 1.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.5rem
---

## Brand & Style

This design system establishes a high-precision, mission-critical interface for additive manufacturing engineers, quality control specialists, and metallurgical researchers monitoring Laser Powder Bed Fusion (LPBF) metal 3D printing in real time. 

The aesthetic is anchored in an **Industrial Technical & Cyber-Physical** style:
- **Tone:** Authoritative, uncompromisingly precise, scientific, and diagnostic.
- **Visual Stance:** Deep slate-navy surfaces mimicking advanced factory sensor consoles and cleanrooms, punctuated by hyper-focused luminescent markers (laser-bed thermography, optical emission alerts, and machine vision bounding boxes).
- **Korean Typographic Naturalism:** UI copy is fully localized in Korean (한국어), maintaining terse, professional technical terms (e.g., 레이어 두께, 분말 도포 균일도, 키홀 결함, 레이저 용융지 분석) with metric-standard numeric formatting and monospaced diagnostic telemetry.

## Colors

The palette directly models real-world industrial additive diagnostics—the dark ambient interior of a vacuum build chamber illuminated by high-energy laser optical melt pools and computer vision inference meshes.

### Color Tiers
- **Canvas Base (`#0B0F17`):** Deepest slate obsidian for overall application canvas and viewport framing.
- **Surface Elevation 1 (`#131B2E`):** Core panels, diagnostic sidebars, layer inspector drawers.
- **Surface Elevation 2 (`#1E293B`):** Interactive card backgrounds, table row active states, viewport control floating islands.
- **Primary Accent (`#00F0FF` - Electric Cyan):** Active machine telemetry, crosshairs, nominal laser tracking path, validated layer boundaries, primary interactive highlights.
- **Secondary Accent (`#F59E0B` - Laser Sinter Amber):** Thermal warning thresholds, recoater blade friction anomalies, pre-heating zone variance.
- **Critical / Defect (`#EF4444` - Industrial Alert Red):** Porosity formation, keyhole defects, lack-of-fusion alerts, balling anomalies, bounding box error tags.
- **Functional Neutral / Wireframe (`#334155` / `#64748B`):** Calibration grid lines, inactive telemetry baselines, chamber axis markings.
- **High-Readability Text (`#F8FAFC` / `#94A3B8`):** Maximum contrast ratios for fast readability in dim production environments.

## Typography

The typography system pairs **Inter** for clean, legible structural UI labels and localized Korean text, with **JetBrains Mono** for hardware metrics, spatial coordinates (X/Y/Z mm), melt pool temperature readings, and inference timestamps.

- Korean characters adhere to system fallbacks (`Pretendard`, `Apple SD Gothic Neo`, `Malgun Gothic`) maintaining identical visual weights to Inter.
- Numeric data, serial numbers, microsecond timestamps (`HH:mm:ss.SSS`), and coordinates always render in `JetBrains Mono` with tabular numerals (`tnum`) enabled to eliminate layout jitter during high-frequency telemetry updates.

## Layout & Spacing

The layout employs a high-density, multi-pane workbench optimized for widescreen industrial workstations (1920x1080 and 4K displays), scaling down predictably for tablet-based field maintenance devices.

- **Primary Workbench Structure:** A 4-quadrant layout model featuring:
  1. Top bar: Build state summary, machine telemetry, Korean build phase (`분말 적층 중`, `레이저 스캔 중`, `정상 가동`).
  2. Main Viewport (70% width or 8 cols): Real-time optical/IR layer feed with overlaid vector bounding boxes and crosshairs.
  3. Right Diagnostic Rail (30% width or 4 cols): Real-time defect log, melt pool sensor plots, and AI confidence gauges.
  4. Bottom Strip: Time-series layer scrubber (0 to N layers) with defect heat tick-marks.
- **Density Philosophy:** Compact spacing (`space-xs` to `space-md`) minimizes redundant blank space to prevent scrolling while engineers analyze multi-axis telemetry under critical run conditions.
- **Breakpoints:**
  - Desktop (>1280px): Fixed viewport with split side-by-side analytical stream.
  - Tablet (768px - 1279px): Collapsible defect panel into modal bottom drawer.
  - Mobile (<768px): Alert triage mode prioritizing status badges, critical notifications, and live stream frame capture only.

## Elevation & Depth

To avoid visual noise in sensor data visualization, the system eschews heavy blurry drop shadows in favor of **Tonal Layering** and **Technical Ghost Borders**:

- **Substrate Base (Z-0):** `#0B0F17` pure solid background canvas.
- **Diagnostic Panel (Z-1):** `#131B2E` with a 1px crisp hairline border of `rgba(51, 65, 85, 0.6)`.
- **Active Focus / Floating Control Bar (Z-2):** `#1E293B` surrounded by a subtle low-diffusion cyan highlight (`0 0 12px rgba(0, 240, 255, 0.15)`) and a `rgba(0, 240, 255, 0.3)` hairline edge.
- **Defect Critical Pin / Callout Overlay (Z-3):** Floating diagnostic popover with crisp alert red border (`#EF4444`) and semi-translucent backdrop filter (`backdrop-filter: blur(8px)`, background `rgba(19, 27, 46, 0.85)`).

## Shapes

The interface utilizes tight, engineered corner radii (`roundedness: 1`, 0.25rem base) reflecting machined metallic blocks, milled calibration plates, and industrial equipment consoles.

- Standard buttons, numeric badges, table cells, and input fields use `4px` (`0.25rem`) corner rounding.
- Machine vision bounding boxes and layer target crosshairs maintain `0px` sharp corners to maintain mathematical accuracy across optical pixel coordinates.
- System status pills and alert tags employ a subtle `4px` maximum radius to avoid looking like soft consumer-facing capsules.

## Components

### 1. Optical Viewport & Bounding Box Overlays
- **Defect Markers:** 1px stroke bounding rectangles colored according to defect classification:
  - Keyhole Defect (`키홀 결함`): `#EF4444` solid border with 10% fill and corner crosshair markers.
  - Lack of Fusion (`미용융`): `#F59E0B` dashed 1px border.
  - Balling / Spatter (`스패터/볼링`): `#38BDF8` dotted border.
- **Overlay HUD Badge:** Anchored to bounding box top-left: `label-sm` monospace badge with defect name, confidence score (`98.4%`), and coordinates `X:142.12 Y:88.40`.

### 2. Buttons & Trigger Actions
- **Primary Industrial Trigger (e.g., `스캔 일시정지`, `분석 재개`):** Background `#00F0FF` with `#0B0F17` bold typography. Active state adds an electric cyan rim glow (`box-shadow: 0 0 10px rgba(0, 240, 255, 0.4)`).
- **Secondary Diagnostic Trigger:** Background `#1E293B`, 1px border `#334155`, text `#F8FAFC`. Hover switches border to `#00F0FF`.
- **E-Stop / Emergency Mark (e.g., `비상 정지`, `레이저 즉시 차단`):** High-visibility red background `#EF4444` with high-contrast `#FFFFFF` text.

### 3. Metric Telemetry Cards (계측 진단 카드)
- Dark plate background (`#131B2E`) with a 1px border (`#1E293B`).
- Subtitle in `body-sm` (`#94A3B8`), primary metric in `label-lg` (`JetBrains Mono`, `#F8FAFC`), and delta rate colored cyan (`+0.04 mm/s`) or alert red if breaching tolerance.
- Integrated mini sparkline showing the past 100 layers of powder recoater uniformity.

### 4. Input Fields & Parameter Controls
- Inputs use `#0B0F17` inset styling with `#334155` border.
- Focus state activates a 1px `#00F0FF` crisp outline with zero border-radius shift.
- Labels are strictly bilingual-aware (e.g., `레이저 파워 [W]`, `스캔 속도 [mm/s]`, `노출 시간 [μs]`) in `label-md`.

### 5. Korean Layer List & Defect Table
- Row heights compressed to 36px for dense inspection workflows.
- Alternate zebra striping using `#131B2E` and `#101726`.
- Status chips:
  - `정상 (Nominal)`: Background `rgba(0, 240, 255, 0.1)`, text `#00F0FF`.
  - `경고 (Warning)`: Background `rgba(245, 158, 11, 0.1)`, text `#F59E0B`.
  - `불량 (Critical)`: Background `rgba(239, 68, 68, 0.1)`, text `#EF4444`.