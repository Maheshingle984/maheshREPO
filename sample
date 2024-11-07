export default function json2html(data) {
    let html = `<table data-user="jinglemahesh984@gmail.com">
                    <thead>
                        <tr>
                            <th>Name</th>
                            <th>Age</th>
                            <th>Gender</th>
                        </tr>
                    </thead>
                    <tbody>`;

    data.forEach(item => {
        html += `<tr>
                    <td>${item.name || ''}</td>
                    <td>${item.age || ''}</td>
                    <td>${item.gender || ''}</td>
                 </tr>`;
    });

    html += </tbody></table>;
    return html;
}
