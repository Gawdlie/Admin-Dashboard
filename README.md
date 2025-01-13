# Admin-Dashboard
Intermediate Admin Dashboard Project using grid and flexbox!


Planning:

full container {
    Grid: 2 main column containers - one being the sidebar and the other being the content

    content container is 4-5x the size of sidebar

    in sidebar {
        We can use Flexbox, flex-direction column for this portion

        min-height: 100%

        3 div containers
            - one for dashboard header
            - one for main features
            - one for bottom features
    }

    content {
        We can use Flexbox first:

        two main content containers
            - top sub container:
                - search bar/icon, bell, pfp, name
                -pfp, intro, @
                - 3 buttons
            
            - bottom sub-container
                Use Grid for left half, 2 columns
                Use Flexbox for other half
    }
}