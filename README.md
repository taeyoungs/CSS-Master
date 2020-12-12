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
- [x] Justify Content, Align Content and Place Content
- [x] Justify Items, Align Items and Place Items
- [x] Grid Column, Column Start and End
- [x] Line Naming
- [x] Grid Row, Row Start and End
- [x] Grid Area
- [x] Justify, Align, Place Self

# Using CSS4

- [x] Installing Parcel
- [x] Configuring PostCSS
- [x] Testing

# CSS4 Awesomeness

- [x] :matches , :not
- [x] CSS Variables
- [x] @custom-selector
- [x] @custom-media
- [x] Media Query Ranges
- [x] color-mod, gray(), system-ui
- [x] Nesting Rules

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

## Tip 1

    "files.associations": {
        "*.css": "postcss"
    }

적용시키니깐 vscode가 원래 인식하던걸 인식 못하게 된 것 같다. 😕

## Tip 2

postcss에서 더 이상 color-mod를 지원하지 않는다. (2018 ~)<br>
그래서 따로 plugin을 설치해주고 사용하도록 하자. 🤪

## 19.09.06

| CSS Grid (2/2) & CSS4 (3/4)

1.  gridbox가 가진 flexbox와 유사한 속성<br>
    justify-content (가로 위치), align-content (세로 위치) place-content (가로 & 세로)<br>
    단, box 전체를 움직이는 속성
2.  grid container 안에 존재하는 item들을 조정하는 속성<br>
    justify-items, align-items, place-items<br>
    단, default는 strecth로 설정을 따로 안했다면 strecth된 상태로 출력
3.  grid column or row<br>
    line을 기준으로 어느 라인부터 어느 라인까지 영역을 차지할 수 있는지 정하는 속성
4.  line naming - 이름 그대로 선에 이름을 부여<br>
    ex) 마지막 라인을 end-line으로 정한다는 등
5.  grid-auto-flow 속성값 중 dense - 알아서 item을 끌어와서 빈칸을 채워줌
6.  grid-area : row start / column start / row end / column end
7.  CSS4

        /*
        #1 CSS Variables

        :root {
            --awesomeColor: 1px solid red;
        }

        li:first-child {
            border: var(--awesomeColor)
        }

        #2 :matches & :not

        a:matches(.target) {
            color: gray(20);
        }

        a:not(.target) {
            text-decoration: none;
        }

        #3 Custom-selector & Custom-media

        @custom-media --ipad-size (300px < width <= 850px);
        @custom-selector --heading h1, h2, h3, h4, h5;

        @media (--ipad-size) {
            body {
                background-color: #ffbe76;
            }
        }
        */
