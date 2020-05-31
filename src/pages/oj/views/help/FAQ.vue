<template>
  <panel>
    <div slot="title">{{$t('m.Frequently_Asked_Questions')}}</div>
    <div class="content markdown-body">
      <ul>
        <li>{{$t('m.Where_is_the_input_and_the_output')}} 
          <p>{{$t('m.Where_is_the_input_and_the_output_answer_part_1')}} <code>stdin</code> ('{{$t('m.Standard_Input')}}') {{$t('m.Where_is_the_input_and_the_output_answer_part_3')}} <code>stdout</code>
            ('{{$t('m.Standard_Output')}}') {{$t('m.Where_is_the_input_and_the_output_answer_part_5')}} <code>input()</code> {{$t('m.Where_is_the_input_and_the_output_answer_part_6')}} <code>sys</code>
            {{$t('m.Where_is_the_input_and_the_output_answer_part_7')}} <code>sys.stdin</code> {{$t('m.Where_is_the_input_and_the_output_answer_part_8')}} <code>print()</code> {{$t('m.Where_is_the_input_and_the_output_answer_part_9')}} <code>{{$t('m.Runtime_Error')}}</code>
            {{$t('m.Where_is_the_input_and_the_output_answer_part_10')}}.
          </p>
        </li>
        <li>{{$t('m.What_is_the_meaning_of_submission_execution_time')}} 
        <p>{{$t('m.What_is_the_meaning_of_submission_execution_time_answer')}} 
        </p>
        </li>
        <li>{{$t('m.How_to_report_bugs')}}
          <p>{{$t('m.How_to_report_bugs_answer_part_1')}} <a href="https://github.com/QingdaoU/OnlineJudge">Github</a>
            {{$t('m.How_to_report_bugs_answer_part_2')}}
          </p>
        </li>
      </ul>
    </div>
  </panel>
</template>

<script>
</script>

<style lang="less" scoped>
  .content {
    font-size: 16px;
    margin: 0 50px 40px 50px;
    > ul {
      list-style: disc;
      li {
        font-size: 16px;
        margin-top: 20px;
        &:first-child {
          margin-top: 0;
        }
        p {
          font-size: 14px;
          margin-top: 5px;
        }
      }
    }
  }
</style>
