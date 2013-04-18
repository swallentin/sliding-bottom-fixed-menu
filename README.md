percentages.html uses hover event to transition an open and close bar. This was my first solution, but won't work with the project layout, as it's 'fluid' in height and width (breaks design).

js-transition-hover.html uses another approach using JavaScript, allowing the use of a customized initial height of the bottom-bar and assigning a custom "top" margin while bottom-bar is expanded.

js-transition-button.html builds upon js-transition-hover but uses click on button to expand or contract the bottom-bar.

js-transition-button-backdrop.html builds upon js-transition-button but attaches to the html document for click events thus enabling enabled disabled functionality when clicking outside of the bottom-bar.

