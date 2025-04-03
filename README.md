

/* For screens smaller than 768px (Tablets and smaller) */
@media screen and (max-width: 768px) {
    /* General container adjustments */
    .container {
        padding: 10px;
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    /* Tab buttons */
    .tab_box {
        flex-direction: column;
        gap: 10px; /* Adds spacing between buttons */
        height: auto;
    }

    .tab_box .tab_btn {
        width: 100%;
        text-align: center;
        font-size: 16px;
        padding: 12px;
        border-radius: 8px;
        transition: background-color 0.3s ease;
    }

    /* Timeline panels */
    .timeline > li > .timeline-panel {
        width: 95%;
        margin: 15px auto;
        padding: 15px;
        border: 1px solid rgba(255, 255, 255, 0.3); /* Subtle border */
        background: rgba(255, 255, 255, 0.1); /* Transparent background */
        color: white; /* Text color to match the design */
        border-radius: 8px;
        box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); /* Subtle shadow */
    }

    /* Timeline vertical line adjustments */
    .timeline:before {
        left: 5%;
        width: 2px;
        background: rgba(255, 255, 255, 0.5); /* Subtle transparent line */
    }

    /* Hide badges for better alignment */
    .timeline-badge {
        display: none;
    }

    /* Adjust timeline item alignment */
    .timeline > li {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
    }

    .timeline > li > .timeline-panel {
        margin-left: 15px;
    }
}

/* For screens smaller than 480px (Mobile Phones) */
@media screen and (max-width: 480px) {
    /* Adjust body font size */
    body {
        font-size: 14px;
    }

    /* Tab buttons */
    .tab_box .tab_btn {
        font-size: 14px;
        padding: 10px;
    }

    /* Timeline panels further adjustments */
    .timeline > li > .timeline-panel {
        width: 100%;
        padding: 10px;
        font-size: 0.85em; /* Smaller text size for better fit */
    }

    /* Vertical timeline line */
    .timeline:before {
        left: 10px; /* Adjust line to align properly */
    }

    /* Center-align all content for compact view */
    .timeline-body > p,
    .timeline-body > ul {
        text-align: center;
    }
}

button {
    display: block;
    margin: 8px auto; /* Center-align button with spacing */
    font-family: 'Audiowide', cursive;
    background-color: rgba(255, 255, 255, 0.15);
    color: white;
    border: none;
    padding: 10px 20px;
    font-size: 18px;
    cursor: pointer;
    border-radius: 8px;
    transition: background-color 0.3s;
    text-align: center;
}.timeline > li > .timeline-panel {
    display: block;
    margin: 8px 0; /* Add vertical spacing */
    width: 45%; /* Adjusted for desktop */
    float: left;
    padding: 20px;
    border: 1px solid rgba(255, 255, 255, 0.2);
    background-color: rgba(255, 255, 255, 0.15);
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
    text-align: left;
}.tab_box .tab_btn {
    display: block;
    margin: 8px auto; /* Center-align each tab */
    font-size: 18px;
    font-family: 'Audiowide', cursive;
    font-weight: 600;
    color: white;
    background: none;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
    transition: color 0.3s;
    text-align: center;
}
