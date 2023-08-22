<script>
    import SvelteTable from "svelte-table";

    let cols = {};
    let data = {};
</script>

<div>
    <table id="timetable">
        <thead>
            <tr>
                <th>대학</th>
                <th>개설학과</th>
                <th>과정</th>
                <th>이수구분</th>
                <th>과목번호-분반</th>
                <th>과목명</th>
                <th>학점-시간</th>
                <th>담당교수</th>
                <th>폐강</th>
                <th>강의시간</th>
                <th>비고</th>
            </tr>
        </thead>
        <tbody>

        </tbody>
    </table>
    <SvelteTable
        columns={cols}
        rows={data}
        classNameTable={['table table-striped']}
        classNameThead={['table-primary']}
        classNameSelect={['custom-select']}
    />
</div>

<style>

</style>
