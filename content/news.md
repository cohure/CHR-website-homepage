---
title: "News"
---
<style>
    div.news {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(min(320px, 100%), 1fr));
        grid-column-gap: 24px;
        grid-row-gap: 24px;
    }
    .new {
        /*border: 1px solid;*/
        display: flex;
        flex-direction: column;
    }

    .new .content {
        padding: 0 0rem 1rem 0rem;
        display: flex;
        flex-direction: column;
        flex-grow: 1;
    }

    .new .content h3 {
        margin-bottom: 0px;
    }
    .new img {
        width: 100%;
        aspect-ratio: 2/1;
        object-fit: cover;
        object-position: 100% 0;
    }

    p {
        font-size: 1rem;
    }

    .link-button {
        display: inline-block;
        padding: 0.5rem 1rem;
        border: 1px solid;
        border-radius: 24px;
        margin-top: auto;
        align-self: flex-start;
        text-decoration: none !important;
    }
</style>

<div class="news">
    <div class="new">
        <a href="/news/new_board_members"><img src="/images/news/CHR announcements.001.jpeg" alt="Announcement board members"></a>
        <div class="content">
            <h3>New CHR board members</h3>
            <p>
We recently welcomed two new members to the Computational Humanities Research (CHR) board. ...
            </p>
            <a class="link-button" href="/news/new_board_members" aria-label="Press to read about new CHR board members">Read More</a>
        </div>
    </div>
    <div class="new">
        <a href="/news/chr2025-in-luxembourg"><img src="/images/news/chr2025-luxembourg.jpg" alt="Foto of buildings in Luxembourg, covered in snow"></a>
        <div class="content">
            <h3>CHR 2025 in Luxembourg</h3>
            <p>
The 6th edition of the Computational Humanities Research (CHR) conference will take place at the Luxembourg Centre for Contemporary and Digital History (C²DH) at the University of Luxembourg from 9 to 12 December 2025. We look forward to continuing our discussions in Luxembourg! ...
            </p>
            <a class="link-button" href="/news/chr2025-in-luxembourg" aria-label="Press to read about CHR2025 in Luxeumbourg">Read More</a>
        </div>
    </div>
</div>