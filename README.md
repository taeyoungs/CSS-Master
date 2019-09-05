# CSS-Master

CSS Next, CSS Grid, Flexbox ...

# CSS Flex

- [x] CSS Flex Basics
- [x] Main Axis and Cross Axis
- [x] Flex Direction
- [x] Flex Wrap
- [x] Align Self

# CSS Grid

- [x] CSS Grid Basics ( Row, columns and gaps)
- [x] Auto columns, auto rows
- [x] Template Areas
- [x] fr unit, repeat
- [x] minmax, max-content, min-content
- [x] auto-fill, auto-fit
- [ ] Justify Content, Align Content and Place Content
- [ ] Justify Items, Align Items and Place Items
- [ ] Grid Column, Column Start and End
- [ ] Line Naming
- [ ] Grid Row, Row Start and End
- [ ] Grid Area
- [ ] Justify, Align, Place Self

# Using CSS4

- [ ] Installing Parcel
- [ ] Configuring PostCSS
- [ ] Testing

# CSS4 Awesomeness

- [ ] :matches , :not
- [ ] CSS Variables
- [ ] @custom-selector
- [ ] @custom-media
- [ ] Media Query Ranges
- [ ] color-mod, gray(), system-ui
- [ ] Nesting Rules

# Conclusions

- [ ] CSS Grid Kiss
- [ ] Practice Flexbox
- [ ] Practice Grid

# 정리

## 19.09.04

| flex-direction

1. row - main axis 수평, cross axis 수직
2. column - main axis 수직, cross axis 수평
3. flex-wrap - 흘러넘침을 제어할 수 있는 속성
4. align-self(flex items에게 직접 적용) - cross axis control

## 19.09.05

| CSS Grid (1/2)

1. table system에 기반한 CSS-grid, flexbox가 가진 부족한 점을 해결
2. rows, columns의 개념을 사용
3. grid-templates-area를 통해 내가 원하는 영역을 구성 가능
4. grid-auto-' ' 로 자동으로 rows, columns 생성 가능
5. flex-direction과 비슷한 grid-auto-flow라는 속성을 가지고 있다.
6. fr, repeat(), minmax(), max-content, min-content 😁
7. auto-fill : 최대한 많은 columns ro rows를 생성하려고 한다. ghost-grid를 만들며 미리 영역을 만들고 content를 받아와서 영역에 집어넣는 방식
8. auto-fit : 정의한 content를 받아와서 사이즈에 맡게 브라우저에 펼쳐준다. 미리 영역을 만들지 않으며 content를 몇 개 받아올 지 모르는 상황에 유용하다.
